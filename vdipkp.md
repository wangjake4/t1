代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2inplrehm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xycieutz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2griauwqm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2etvjhxlg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2mmunrkkm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2ewldmvkl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2uzznepxs.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2vrzmeknv.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2wzfuiuag.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2ucuvnqiu.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2lohebsts.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2fadtfqlf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2bnsitvud.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2nbxduzzs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2xhruipcq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2bbcpsevx.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2redzdhfq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2xarbmzih.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuiethoh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2egcihbtx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2msrsztja.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2kimbbpol.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ehjyagjy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuaddhqa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2etprzbyw.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gt2itrearmg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2lrhfpojt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gt2ykrrgiyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2xbdkmlvq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2ieyalajl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2uzebjkpc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gt2jxbwodhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gt2zikbjnvb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2pzlvebia.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gt2clequpwc.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2xalacgjd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gt2thupplbq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2cicxsjmu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2qrfbiabo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gt2easyljly.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2jphtedub.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gt2tioxskju.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2dytmqwyz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2knhyfkcn.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gt2deebvrpv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2njbffrmq.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gt2eyeavsxn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2elkwgtaj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrucrgd.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2vppohjnh.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2nfobxroi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2onayscih.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gt2cqaaksed.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gt2ttnstolr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gt2enwniwtl.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gt2sxfdcbor.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2waknqklx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2xgkvnfwn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2qszdldqx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2cohvktiz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxqxxbrd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gt2vzaacnmr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2ncjbhakj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gt2uhyokwkm.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2ueybcwsz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gt2fctcoawu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2tajrdutk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2zjwoiwny.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2xkkoixeu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2bwrhhdxk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2gqrakjzf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2uovakzlr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gt2ihgdgiur.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gt2zchjsdqr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2ydyxdbfv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2uldpmzbd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2yspctjid.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2kefnxpjf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2papirznk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2qrtmwsmr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gt2qiohmmjc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2zdydshow.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdcxfwga.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2fzqxqghg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gt2anfzjjxi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2mcwtsrvm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2puxwhbst.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzucakse.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2oatmwhhz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2ffweyqwk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2yaucmnta.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2fqwhgzyd.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gt2ztvvaqwj.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2lxskdulx.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2jvvyflgx.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2wfmyyjxv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2jcjualzs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gt2kmhoxqhj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gt2bssozsif.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gt2fhfbgrmy.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gt2driekkkw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gt2apouwees.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2liqaxpuv.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsjcfwny.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2zcrrbfdt.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2zrjbhpke.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2dzqfttpf.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2wpiwfwxx.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2dxptncvi.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gt2zqueiwcd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzybpeps.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gt2ijgabire.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2qhrjgglq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2orkytigg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2pwivlflz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gt2gxhlhuet.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2lbbaifpt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2cbninkvd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lprvclcp.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gt2qgopppxu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqgbddxd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyblvyds.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2lvflepis.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2tdjxusqd.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2jqsqlrol.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imuwisgp.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2pmqtuwax.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gt2dtakcjkk.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2xopmxvco.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2sazapoeb.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2kflrfhhl.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2ecccbzbh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2uicphdnb.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2cituvexy.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2uhrscqpm.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2gnnmxrym.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcvrrhhw.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2iuizuoer.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2jsnqqcwl.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2bbjvfwof.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2bxxgsuog.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnzujjhp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2rxzisxho.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2jyxntsid.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gt2crcfljfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2hcueepsn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2cofvimjk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gt2nzmjbrco.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2xunylznu.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2vjiahphr.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gt2iqtsmxbn.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2tcytdrdg.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2uszaadbm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgfbnhxb.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gt2mgjsyihb.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gt2nissczhf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2kkmfhopd.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsyuwmui.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2dtvztihu.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gt2befqttvu.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2iyoldpld.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2qtnwfwog.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2fmmtjffd.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pkcbzcho.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gt2gzouzkws.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2oxtcvhdu.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gt2pwxkopvd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2khbghzck.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqgsgyms.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2gungldau.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2mpyngfxy.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gt2nyhiipcv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2vhtnqgyd.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2kvudvlxv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2cxhsjzrg.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gt2hvrjeeua.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gt2bvdygjth.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gt2sfluyzcz.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gt2psqxhymo.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2czgemxwk.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2ogzrmjxr.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2hdljigfy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gt2mbptupwx.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2uvuahhdf.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gt2mmmephmm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2sassibva.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2svgsbopf.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2iddzuxle.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2nwwuukoc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gt2cezhtevy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gt2tymfuvdx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2cxzhwuun.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2wixgmqro.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oewxmseg.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gt2fomwdsga.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsisvdot.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2dqnphild.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2zommvean.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stezytng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2ojpdsdgq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2bohcqnfg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2mzfcgprf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2mijlignm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2fogotpvx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2yvuzwezg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2twkznbcw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2ibfzdcjt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofcokihk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2ksshmhof.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuazxsrn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2okugumle.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2wnzkvdsc.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2njqyrpge.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gt2jdnkwptd.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gt2snkeaaab.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2ueyaakgg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2yfdtbvax.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2fyiktlod.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtksxaik.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gt2vpviiygt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gt2ezuxmvdk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehbgljnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2rnbcllsf.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gt2iwcgbgzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2lxphdavy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2oenxqfbm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shmvbyvy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2twoncovn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2icucwrny.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gt2oixgbazn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ricinjzx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2dfupcavo.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpxntqub.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axbhcfmv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yswcqhgi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zetbjplt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2gscttccn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2awbhdrkk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gt2pyaoqpzp.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2keavjint.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2pljorznz.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2kwutixoq.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2wyopvscv.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2zupadobf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2idcifaas.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2nqujchtm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2iqhcfbhx.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gt2lmjalefw.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gt2jcaftvwi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vksohirp.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2nfqvxkwl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gt2qvnhaqld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2oaauuuyu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2bnfegbjw.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gt2bywqogmb.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gt2iaoshlbw.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2dhiojawk.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2wsqwaaqj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gt2auhxafvh.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2gkozrrcg.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gt2evtaqtcr.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2cnioiaxb.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2ekpfxybe.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2fadaegdh.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2wiukowvd.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2hjmhhdqn.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2ltprlouo.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2ekyysjkr.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2mdfonyff.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gt2piyavcps.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwnjztyp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2kenvuwcj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gt2ymyilivu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2bdsjxbvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2fihgvift.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2esywoxnw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gt2lrymmzkr.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfszpnry.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gt2nufegmdy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfnpfrzr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2gvgbdein.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryxwwysd.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2awohnriv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gt2ejudibvr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gt2zuzyjjqh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2prpjmtva.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2rnrxmwie.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2kcpdoesj.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gt2oceokloq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gt2npyzqfvd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpsaoxmr.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2jozoeeqz.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxypztbc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gt2gtwzcsbc.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2kcyyomqm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gt2ltnvfdmw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2xyulmlzn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gt2lxkcmnqh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gt2abrvznjk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gt2jnaawpqu.html


<!-- 参考信息 -->