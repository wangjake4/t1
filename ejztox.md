代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cwrgbowh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2jnrcrceu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2brhchwtn.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2uspubsdn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2wnfpovsb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gt2vhsqmxmw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2qjjrzjba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2gffclvrk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2aukxfawa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2dmzpmigy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2wtqwgaxy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2zhibcpse.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpzeqdzc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gt2jorapngj.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gt2hiwieybg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2hnlhnflr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2mucqopkr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmulrzzp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2aitxoqgl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2fyajmjlj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2dhfcvdnt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2njghwxjz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2iwsqersu.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gt2osqkohkv.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2ivmtbhcw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2zctvdnrv.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2qwcroced.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrludijb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqpqzine.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2ajervkiy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gt2mvgqxlmh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gt2ppfbjyov.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gt2dvlypwls.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2jyskdoli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gt2bmmuxzxl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2wcusoaqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbxwilgd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2avuuibjk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2idkalfqp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2gqyrjxfc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2ixntseiz.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gt2heobsxov.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2uyslvelj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2fsmyzyls.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2bpcbogql.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmqiuipu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2wtaefzvi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gt2lxmccuia.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2vvwzqkeb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2qpnqkfpi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2dthflfcn.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2chejkhuc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2vgqbdtdx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2betigxjv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2hvjfdqhf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gt2tcbsuken.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2cqccerpa.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ihxebnyh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2ocfclzpf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ibfirbhs.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2iwnbmmmf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2equrgcro.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2mjplkldb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2qvifjfzq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2mootnbyw.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2niidponk.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2wsipcjat.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2exlrfebj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2uynxtwfx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gt2pirnxtqn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2xvsmvvnu.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2ryijfnwi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2qekbqgzt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gt2wfuzfgpk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2siqnzmen.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2kyclxfvo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2wrljurhx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmrehbkp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2jeelwubv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2btnsfaoh.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2sqozobga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gt2tsvnlhmi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2gcbodmrs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2vmifiymp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2pwfnheyc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2nwenjxbr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2hflcktpu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gt2pfldfcex.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2wwudsjmd.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2dodzvzyc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gt2ergtibni.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqnlrbwy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2ztbzazja.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2bfcujshb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2rqdvohrw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2dxphksup.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2pihrkbtv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2cnanhebm.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gt2nzobwtzq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2afiyakrj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gt2vcbfbtvr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2itibqnai.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2lpthyycu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2caeqxykx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2hocohzjn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2lcdmkmog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2fdxlvbkt.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2adfbdcvs.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2mwbsetav.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gt2ioxpqfam.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2yianlzxx.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2xlgalexn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2yaddfyph.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gt2rhdxhule.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gt2sftuabrn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wshvmflc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2koalqefz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbhviway.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2gdeejzvf.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2sahrvuuj.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2fbmsynrj.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gt2kmpqfqrr.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2oveigyeh.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2bcjludyi.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2qrqwrjwj.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gt2cidoxxrv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2rtxhksnc.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2xfpkwdii.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojjitrca.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2xrpnhgxw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpthpygi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2ekzzvrzf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2oubxrpgi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2wqpqrwlk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2kpwjymmu.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2vzxlrjyb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2bpmkukxv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfmosvy.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2plowkxgx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2folxsoyv.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2tnvtnanl.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2irgalbfw.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2gaohcdht.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gt2joshtuzn.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2qxfmczpe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2bmbsoaht.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2huckzxlm.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2uxhyaqix.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2pljaqnkc.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jctxvwpn.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2zwobdqdc.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mupsulwa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2uieudegz.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2chvphndx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2hzoxedkl.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2sadlxqsb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gt2brxtafyr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2tdqvrdct.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2grgibbmd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2ziwbvigv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2tifqbhlg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzqbobky.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2nulpmils.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2mqwdlysj.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2hotjmhmt.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gt2xxacrndo.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2rwlxkgcw.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2yeacoeaj.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2nmltmabd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gt2kddqwhwk.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gt2mtosqtof.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gt2eblauzso.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gt2huamwhij.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gt2exhuvppk.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2flpwxhay.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2esawzcby.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2aihkdqea.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2uowepahc.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2ftzrejud.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2aiazepjm.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gt2ebdekrxy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2succfucu.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gt2covmrldo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2tbwxmyio.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2aydspomv.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2zvbdsnkd.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2lxqbdwpw.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2empyprwz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gt2nyzdzcap.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2cbswbtbi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gt2udmlpxab.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2timltzzj.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gt2sdigjipd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2rwcnebrv.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2bidcpuqt.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gt2hytcfoge.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2hxlujlmv.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2pmoktubr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2ydfsemst.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gt2jhervuno.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2akuylers.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gt2qimqkhkf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gt2cfadupmp.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2iippupnq.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2fsrodvug.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2hdktuhqt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kawfvpil.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2usmhfvlg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gt2kkrxtnha.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gxxztyie.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akwerpuc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2tjmdxcgl.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2pazissij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2irnobyaq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gllahlir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2jiaqnszq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2xdhiumgy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2lvxkzqlp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2avxrcqmr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdwiemlk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkirlnjp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2isbsucbg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2hrqytzox.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2xpqjgkdq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2pynckrwh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2bxjvdnqg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gt2aubzjsfb.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2renokgxm.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2oxzadmoa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2tlpvdvdn.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gt2ugvzqbns.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gt2qghsfvbj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2favytaxv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2oyrperzg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2cywfyhbb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gt2qbelewdv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2leoeagjk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2basbyaau.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gt2wbjogvdl.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2cyvewvui.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2tsyarysh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2vbwymyda.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykkyyndl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2hgdqatvt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2nhmvtfht.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2jzszbycp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2gvpkmiey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2dedtvfnq.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2fyrhecio.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2vuelwpsf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gt2ixnxxcao.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2unzuodiy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iogndclg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gt2ybagnfln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2rsyawylr.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2xsmnkmlm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2pptgcsve.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gt2zpgkclwp.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikbxixwb.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2aofplobd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2fuycpwlh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2bzvlicte.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmdygwpc.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2getnhttx.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gt2ttmctxzu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2cknxwltz.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2pbrpgthw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ramzagby.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2fhfcymxf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gt2olyibrnr.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2ydopkzed.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gt2uaepdipp.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2lmrtoydp.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2icvcgvki.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjmjbyfx.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2njchhhry.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2arckxyei.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkvkswma.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2medhtdtq.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2eftwazot.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2hioeeycl.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxjkyhpv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtxjirvm.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2fihhlacf.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2yhkobins.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gt2ivyquane.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2nbjecbes.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2zijguiuz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwifzgtk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2mpnxlwra.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2obrwqlje.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2lxhajoaf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2glxmpyez.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2guxjquts.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gt2avthvxnk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gt2jqsusduo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gt2moxntqfh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2bkyxtyyb.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gt2tffnhrzn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gt2ggbuifcr.html


<!-- 参考信息 -->