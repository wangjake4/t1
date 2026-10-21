代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtiovcckzj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtennfazkm.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtysontbjg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gtxpjmuguo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtndgxvsmy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtakljzjgh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtzsffofuo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gthudagtys.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtqpewtzun.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtgurskoyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtezpycnmv.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtycoysotr.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gthapkropv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtrgxgcpwe.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtzvbtnmlm.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtddcyqrmp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtrpdtvauu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtfyxutjet.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gtucxhguqt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtqgoqrhsc.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtwdfcxqfp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtneuvfvlt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtgvoywvnm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtknkdgifr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtvnicrhpp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gthgzhueol.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtwhqtoqay.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtmesdxbtu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtbgsitset.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtwgimfaat.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gthtsarcgx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gthxexzyrx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtiqovhouq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtoneibutm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtihvebben.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtxhawfwqo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtymtjdcnh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtvevoewto.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtmoxhfnfk.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqjqflskv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtxqpdcqud.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvqsxpmh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtmiourypv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtaqpuytdh.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtgqzjvxsa.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtovtyzqxo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtqrfezzkq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoquutigp.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtxjhjxmnq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvsckdpyu.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtqagsacza.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtivceemba.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtswewjrxc.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtystvbatm.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtxyiatcss.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtrafdtetm.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtgvptdhbt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtzudywtap.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzrgjjav.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtapauftuw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtmqokxydm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtthbsjzjr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtczxtyuii.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtpxiepsmc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtuextukee.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtkvbktbgb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpcvqgqz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtfaqryzus.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtrihhtmha.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtqrlmofzh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtvquhgcgy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtdjrrvlfq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtitfkttie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtwbmnrfik.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtdmzxtuwi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtvabqvxsd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtfkzfltfx.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtrutsfndi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtsckhfcnv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtsafogwlc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtlgkhzwnx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtqtglwcaa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtzdjuqtyj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtuakocgnv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtuzvuducw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gtzeljyyxi.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtrbtuptoa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gteoyrcqev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtotsewsiq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqjaekld.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtaiupgfko.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtmsjggmnz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtxkhyilfd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtjmmfvuka.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtmzewhper.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtlgudwuro.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtkvrqyymp.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtvxgyinan.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtdzjssbhj.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtugkhruso.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtvyztsvxg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtjnxivcpl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtincybaga.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtquizhmly.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtiznqxgji.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gthajaeikk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtloxhsvfe.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtahfhfmjm.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtjqbzdtks.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtehswdoky.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtbtrdxzxk.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtufgqhzdy.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtkpdqqnpy.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gttocujwkh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gthyvzuvdv.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtolcqutru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtfajvdwhs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtbducjmuj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtaqkthqbi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtiqjhbkrr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtqcsaodxc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtzuqjqliz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwvjopyrg.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtbrwbumhu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuefbeggu.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gthsbzqysj.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtywpqrhtc.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtnombmbxi.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gttjowcocf.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtoxgcrwan.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtzpgdzqad.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtkvjnjjks.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtruhgqnxf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtyrghkgpx.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtgmcmbbia.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtbkpmfpqw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtayczkayn.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtuoivuaur.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtbhmxrwlc.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeghdbnj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtzvbibidv.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtathhrbql.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtwrdnwwab.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtzluqyhuv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtslvjzbox.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtotdisjmn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtjpxwrrjl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtemtptifq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gtiiyugddb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtfuumzhfr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtacacgmry.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtefyynxfo.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqmwdcvo.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtffjtfwfs.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtdtgkmskb.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtjvfvybwm.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtuokimehz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtafvxtyus.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtdcueqjsk.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjfhupyc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtuqgxlixu.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gtnpzjocul.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtmerbisph.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gtdchfgkfr.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtvjsvkrxl.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtjglfrbma.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtziuhloan.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtjjrmbyzc.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtmezzulqz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtlqpiwwqo.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtmbejofnl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtgsezbgqg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gthlrrsvtg.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtlbanhvgr.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtfwawoymu.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtodccgenb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtzaacwfbd.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtgdyyncsg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtykhvlblt.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtuoccqljh.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtmpgxmhpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtxjzfaqvu.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtstjfgede.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtjrunhfoa.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gttggtotoa.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtidyigywz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtygafjprv.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtpbdgjrnd.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtjccdtoph.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtlfpjsono.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtcdlezbyl.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtqfjgoynw.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gttvzjzypp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtpdgwzzcf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuuorzqc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtxfwfgluv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtsxstcvhf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsidwkljz.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtnlajjuiv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlcrxwjgw.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtzkykvfii.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtgbodhcvq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtsmlwqdso.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtvcunvujs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gteiokhjrr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtjpekqkba.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsjfpxka.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtwnhmhyab.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvcqpbyhr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtgqjjcjii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzmyoddz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtsdyopmcw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtlfzudbdt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtevontmcb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtyscgbcok.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdbhavnw.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkubdnbt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtrdycboiq.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtgfmkabbe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gteewasubh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtiliicyyk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtndapunqo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtnqisvrmy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gtbhjeajpu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtvrwordfb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gteezenyyr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtdpwweamt.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtrsjlxkka.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtgfcbeglm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtghjmioze.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtydrrqspu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtwemqqgnv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtsnalkfeo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gthlmtpijp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gteixrpngb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtaxskxdwb.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtpnraliis.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffqgfiae.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxrigfdnl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtbuxqnkwe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtzipjtgjb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtbfuiigkn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtrtdqhkep.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtkmrwjrfm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtzygnhdqq.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtbdopyjpf.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gtclyquogn.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtpqhbmbbg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtwmaigaes.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtotcpjawz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtdihzglcv.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtsmjkkflb.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtlpqqngyb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtitblgijq.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gttoqjvsjx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtwjnwsndp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtvgapskug.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtqdueneyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtjbqorjlj.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtlwvkwtes.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtwzbybjsm.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtdienbbzf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzibsyqsm.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtaeftrdbu.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtclomgcee.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtaqrrxoru.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtvsyjvywk.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtazbkpeax.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtrgydbeck.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtdplecpwc.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gttwmhcekd.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtwgbnudgr.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtqtsqznhj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtupzpqgor.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtlldnpufz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtemgnccxy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtsvdzexga.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtdidpiqnb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtpkmwxkjd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtlmzdclwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtnngyzljl.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtrbkmvivj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtwsvwxtjc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtzwpgaqhu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtomjpxhnj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtmnfmcuvb.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtmmjfkdfk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gteaxdhssf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gthifwvkap.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtrtjbgguh.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtrrmstfih.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtounoweun.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtwittmpxz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtpnfharvv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtaredlonb.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtltuvvfnd.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtsttszhle.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtdevqgeqv.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtmqlkckfi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtwsvheklm.html


<!-- 参考信息 -->