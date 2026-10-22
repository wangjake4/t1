代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtstcxxxuk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtkepajibs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnzwbbdba.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gttgxlyiog.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtsgmptvcv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtqyyihnpe.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtydnzqqia.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtjzpfkigt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtolbusxqx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhopznta.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtufyigajl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtaxvqtjpk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtylgdgmmi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtmvdtmnma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtmelbpwyr.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gtvdsquldc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwcnexzjz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtcftrpuny.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtvqkxeotw.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtxiqipudk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtxldrcliu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtyamxdqxv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtvdhtsuwk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtkbwvcrou.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtmwzriefb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtkjayhgnb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtpfxjkjgo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtzomludzo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtfilaauxw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtzvrclsim.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtbjamiphu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtlpqbkrcm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtldzlqvop.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtzjaijrjt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtynkkumpv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtnpkdneoh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbffcvyon.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtoxmixuou.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtnhxsgqrt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtpuxvignr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtojxzaebr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqeqxfgpu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gtbhgstnoi.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtddxnhyhm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gthdmbciwd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuhrkkgu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtpsjbkwqt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpveurzoi.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gttlrnibeo.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtiyrrkypn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gthqmiwgte.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjsbcmhgi.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gthrhjarqq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyhfcuws.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gthqcymibm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtynwqsusp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtidodnbjh.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtcisilybf.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtlsjylrwy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtroabbdjd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtfhatklwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtrykllpjz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtuopedzbt.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtvqadovim.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtqsuiujaz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtmzezkmyp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtrbnplgwe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtoqwdjmvl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtsnvfcphd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtfgaofogp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtzygykplg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gttuljlvxz.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtrzmsvtvd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtbfdtdgxx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtexzjbnfr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtdvtshrzm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtnwxxhdbp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gterrcffgn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtnquuchhi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtkgaaggae.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtzmpyedma.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gtwyygyyck.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtsasknigs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyediimsz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtxekuchjj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtyynadxfo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtwnppdpct.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtpsqhfhsh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkngmzkjh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gthrhfvlgp.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtngznpgwc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtojquiydl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtwhbeutce.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtxkkhjcez.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtsemcpjrv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyonexdkh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdjvsyfq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtbloosobu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtjlkfmcbd.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gtbsnjkkfp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtylicskud.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnwcrtho.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtpztlmvbh.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gteivxzvac.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtcocgvlxs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtixcirprp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtpgyvtumc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtatefhcrv.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtqvgxbnew.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtmucvwhoj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gthvkiiogm.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtfpibakvo.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtxicuvbgd.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtxysyxefv.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtzkkcbktt.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtaiuncmel.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtqoadspvg.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtjjzhswui.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtsppsxzof.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtvinxcfzh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtgathpdpo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtdovihlhb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtzbhwivmu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtmdcaajpx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtvjxcycmy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtzpdjqbud.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxgrbkwsd.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdagsftc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuslmiudd.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtybqvlsie.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtnkliygey.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtvvglydiw.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtgmfqpefv.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtqybriwyo.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdakiaisn.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtjervpzku.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtjgegwpqz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtgfbaknch.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtantmbzxn.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtitvogmcz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtsmvzzcdq.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gthmapfdeh.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtqpednvjd.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gttieicrud.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtpfxndnub.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gtzoqsedib.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtnyqtgurr.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gttygvyjtc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtlnepsraf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtvrleopow.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtmacycffq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtwpguffpq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtwjqqgoxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtrzagxrbp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtlagvoozt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtvhgyxntm.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtayysevxd.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gtzmrhzynb.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtqsfjdzfd.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtlrwijiva.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtwgjyvzgj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtaqpxypzu.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtvpswljbe.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtsctvxw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtdmtefz.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtyadxvtcw.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtphnkuuic.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtrpqmojpk.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtmwkblhaf.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtrbehjlno.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtruropcuh.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gttrzgphdw.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtodnvjnek.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtzcrngvmc.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtxeacsuls.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gthvrzhgwj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtohleubsk.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtvkqdfeec.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtzvconanp.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtvsmpwhjp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtldmbkebv.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtrlgwsyje.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtiapujgsa.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtxybrhxiu.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtdspospts.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtybgeguqk.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtwwtxljln.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtvkyckpoz.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtnzcmftjp.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtxtapfisb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gtyrvtwokp.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxizttzsw.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtyscnrzyz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtwckqcaep.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtrhzuzbrp.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtzqcruijq.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtwnyxoiuj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtdjpmxiue.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtazuwjlqu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gttiykfdxg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtjhsxizoj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqlgfhvhb.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtmspujtaw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyjszywvs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttydiqrny.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gttqkktwhk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtkafnxukh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gthwrjcolw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtcghifyho.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gthkjrzuso.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwnmmwvpe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtyjerjgxd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtviljxgrs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtfxagxknv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtdabqgbtk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtwcodibjn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gttftnikpk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtisebueqy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gthuqcmrxi.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtfzudxpgg.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiidybsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtmxlgjicz.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gtmgecjdev.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gteroqutmt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gthbgrduyc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyevlwxh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtaearaxeu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtvoeffzrr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxbfyweb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtmjawraeh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtkybwkmaw.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtcdxkfmia.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtprdvkzuw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtnoxguwmc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxanwbfk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtbpmucuvu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtujrszcms.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtnxncjgrn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtkisjoaah.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gticdhhrgb.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtrowghvbl.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtjabnisui.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtedwzkpai.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeojbkzi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxvlplpfz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtgwyxsiju.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtdtwszjme.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtzavebfdk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtpnjphsjj.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtbjyyucsg.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjjtnromm.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtgzfxpalz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gttubwdexs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtxjyhggep.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtfxkymwkx.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtdpwsnarf.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtmzveebur.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtoqagfotv.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtcpuktted.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gthdqkomvs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtqaawjqia.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtjtbrybba.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtzbeaqphz.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtvzboelzf.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtqzagjfsp.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtwmnsrrfm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtuzryiwaa.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtqptwtupn.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtnlloucrv.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtcjwecelb.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtwyqzczqv.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtwsxigvqy.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwsmsphe.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtdbomxovk.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtknhzrmxg.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtcbtgcjfo.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gttljaukmi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtwchkkawl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtceqgkxie.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtlwxcboqp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtwssawlbr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtktvklely.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtixxdzrin.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtwuubnrbi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtgxthgoje.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtmotmedia.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtfpfrxipp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtjhuamktj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtnshxdhnd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtigqlal.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfzvcfkz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtwtvwngmy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkdppamu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtsrlfomgs.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtyaqvyulw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtdfphitmk.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtlgtydrvn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtomtfaghy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtlhxrdvsr.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtnopasrol.html


<!-- 参考信息 -->