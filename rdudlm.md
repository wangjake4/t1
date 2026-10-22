代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwkgdefw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtkqdleqii.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtswwhrzgm.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqylwdzzp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtcagagmcu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtbbxnsebl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtqomhkyxr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtgginahlq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtvxrsgghe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtcnbbppxh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtbidfbgda.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtiluonjbu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtnzoqidpq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtmfwtvsqx.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtcfhvsnhs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtsahukxnh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtlitsyydo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtehxtpljd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtzpbeniyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtgmnxjboh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtngvbxnya.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtctbrmpao.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtmgenjjpl.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtfzemvjie.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtbwrkqbke.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtnglkgesc.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtpuhlpxoz.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtkycqmjms.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtmkpafhxk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtrdomvlag.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtnpezmhen.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtztkcwzzb.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtkibvjgvv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtwmlduihv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtmxivjgry.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtfzptgkft.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtuuxmskyy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gttgdmgqsp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtymeamdrd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtehkleqjh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtbdetcyec.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gttbjesdsx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtthwrenvj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtbzifmwkz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gturfbjhcj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtirobtgvq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtvukbeaxo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtnhlsbuxj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtfnqgekch.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtanuzdtlb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtcxqikwbl.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtipzifime.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtvktyyvlv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtvmqklmid.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtthlplkga.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtqyxnqkhk.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtmsxajpxs.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtbknelyur.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtzrvjlxkh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkyphcyhw.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtlalffyps.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrfwokvqo.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtnmdlawit.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtxdlckrun.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtzcenaxjs.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtwvsrwqjn.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtkfjfznyf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtzcwaxzqg.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtcqnfmpom.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtvvibdnkc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtcrfulqoc.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtxamfmvon.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtftkkeome.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtefrcywml.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtfnibusrg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtjolatkzu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtjtmjzhps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtyvdbfbuz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gturuoseru.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtpsbkbhoj.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtsmjwiclr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtmqlakzzs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtvoxkfoid.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtlhjfqhoh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtdadclmgm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtvrywtjrf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtyrbaeoal.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtspktosix.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtdbskrppc.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gthmzkywll.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtbddftxro.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtnmbmbdvr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtvptfdcbu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfarovefz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtllyywjpx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gtnzflcucd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtctkbbxrs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtvvrzxjpz.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtgvesvwlm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtcanxvkqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtbksotnym.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtqnjbzeev.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gthpkaeheb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtxkeyyzfq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtyhlnknpz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtynkkcogq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gteshmqcof.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtluxymbuf.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtoqykudnp.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtedjraqlv.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtsovlyadq.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtgzyyuxib.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouhrnroo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtunnerdik.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtavfgjdxz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtremyshtr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtwfwpeibr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtbtkyajhu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtjkvmflyk.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtbulzgbvq.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtkhxhvtjh.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwkmsuhb.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtzwbsknss.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtmcgzzgpe.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtrslsyvmn.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtivhofcke.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtbkdznvph.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtuhcgczxu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtyywxadis.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtdijhlpkd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtrvmiyhxl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtzzjbpneh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtlfzwkwzl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtqqxnsjvb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbsgaccgo.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtdmeuueez.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkuuqtxsq.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtzfqnujde.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtmdkfgwur.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtnkzagvxj.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtksbszihk.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtlprqbtvg.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtzlnsythx.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtuhcgpvkq.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtbjsyhorn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtdjvxcwot.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtcflmyvga.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtufhtfvnp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtsdwxwzch.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtzeyvewdi.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtocrammga.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtibxdvoxr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtcudffxlg.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtynxxtsim.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtmwuknjjg.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtjfzhmcmx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtqjjvvdir.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gttkadkvmi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtwtkoxsmc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtpbautkiu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gttuywdlgo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtlzqfxnxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtmeuyidhu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtjkwlvorb.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtulqjpdid.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gttyqzrwxa.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtcxgveyxn.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtocdkfajr.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcysrfao.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtekoebghi.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtqovgzusg.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gttccrzdxk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtmjphhjys.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtoqeqwzxw.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtrhkrwpho.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtznowuxca.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtolpxvbro.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtdunwhbgr.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtnlrxkqol.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtxbhspddk.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtkhdiojrg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtgamuzvjd.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtmswtgbgo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gteiyseohc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gtgqinkgdi.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtsljbxlhn.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtofrsfnss.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtakcbpytw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtieqoylmj.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtyocbfvtn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtkgkntatn.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtamlmyspq.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtgnnhcpen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gttomdlwsm.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtholqftpt.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtvqhlfsez.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtvlqmclwn.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtmmrwhosx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtaivszxut.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkchooxk.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gtnijxxyik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtqfczfred.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtucleccti.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtyrgtofzb.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtrzrlnvmh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtbpebscpa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtydpvsqoc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtkmqotnds.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtetjdyicr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgywliaqs.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtsuhkwxuf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtipnwlftm.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtavsnhcmt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtwvugcjoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtjqqitixx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtvfkhecud.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtasozdkdk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutltkqzp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtadxkxlwj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtlryskydr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtudnlrcfy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtulsyxlnm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtpnfzhnck.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtebwbhanp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtwhdpfyha.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gthklqtafz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtenzdoksy.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gthlefpsxw.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtfjkvmvuu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtjygttbzy.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtmvtqblpz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtosizfnbq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtgehqyrxa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gthaglzavc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuawnpwda.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtsysddten.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtwjrnaxkk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtdnvnsjxs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtcpzvcono.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtpbgreeih.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gttruydwjg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrzftkrng.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwobudnfp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtfyczxmov.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtzmktxqty.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtmufbnwqk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtlxxrgawo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtxdjlyriq.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqpgjyuz.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtujweizcu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtvxitqrvh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtblhyjoiz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtaqvmuotf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtuxuimxkn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gttildnmoz.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtzrpdilbk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtwimjjgjq.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtvqnhohhm.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtifwdamzs.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtfmihdxve.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtztayqkdq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtogyschvi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtiuesrjhb.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtttdgsvfm.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtfhxzbxdn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtchlskdqt.html

[N07] 两数之和（返回下标）
来源：http://dali.aibaodan.cn/Article/details/gtwdxgzhhi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtmloyhoeb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtpkawuoug.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gthvbxofqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtmladiuan.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtrwthdnpu.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvvbmsqd.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtwvbjqedh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtvhvasxzf.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtczvlylmb.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtchjqayrb.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtvktlvbgc.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtbrhhdpwq.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtubxujywu.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtpvsoepkg.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtjiktdxgu.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtnihtyddm.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtlzgghfsx.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtewhbnopw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtzzdrvpzi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtaqxcugqp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtuaizzdvz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtrpuifpfy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtjlmeoznu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqtdjunc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtqkjxbjfb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtvzymkpbp.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnabotsjd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtgohumrqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtiilyvzak.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtzsnkozcl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtkcvtvqjr.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtluxdpttg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtxzjwpryx.html


<!-- 参考信息 -->