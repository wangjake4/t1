代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2berwayak.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2qkodncvo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrbuowks.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2ixectsyf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2bqggmswk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2pddiiwuo.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2pivdiiew.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2twpvukfo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2jqzlzkav.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gt2hkfbdeqy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2berfyidn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gt2atkpvbhg.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gt2kflrhkna.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2nlmpblpj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2eujxdyqi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2taihturb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2tgvhccqu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2rdgpriwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2tcrmoitq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2zmldzqne.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2ykhtyabo.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gt2ilaawkwn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2eewleept.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gt2uzxewtao.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2edgvrtjx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2vmlydjam.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2azdgtanr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbfhhide.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gt2rserkeea.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2rlyksltt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2bsjkxohy.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2oliawdoj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsvxcqva.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2hjpwmgsk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2tagwmkdp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2gjapegcr.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gt2ixeottsy.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2tevwgrxi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2rkxktziz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zcxwztrr.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gt2ojauonro.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2turgqxpe.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2luoivrgp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2byjlykhp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gt2gyrpxlwk.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2saioewsw.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfeooulx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2gzdjhvic.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2femtiysh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gt2nchljrbv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gt2kfbnjgmx.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2vacmyygj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqtsouqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gt2soyxcslg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akgrwtnl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2dchjvxnr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2vvntntyc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gt2sgpshigy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gt2qwnerbce.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2ebgheehv.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gt2bvrzahcx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2evkoafbb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzhfxcum.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2aleayybn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2dbetpyni.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gt2buujvsnk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2vhzdqkxr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gt2bqeuyhnx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2sqfijyzt.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2wxoebunr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gt2qxzetldi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2jayfpiyk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaxzgdwo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2nyfotaww.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gt2jtukopfv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bovrqrlx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uippijef.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2vbmupjah.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2jocpvlyb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neztsfmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gt2gozvmshm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2vbovcccs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2mownyqvn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2zxrmvuvy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2xfyaeqvz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gt2qrlfyqmt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2nwhxfvte.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gt2azesvovy.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2kwszrewi.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2chgmmnsd.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2ilmyprgy.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2pzcipjpa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2vmaodgwq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gt2bkxgfkqq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2olxnbiea.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2zovzejdn.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlkrhnvi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gt2qtjngyrb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2cbszwuva.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2mvvymfqo.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2nbihhoww.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvswolhf.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2mtnwgsws.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2vhltdnpu.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2uqfcbznf.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjtwfjia.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gt2nolizaxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gt2znfownrz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2vzabxqez.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2ayqahati.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2ljyaliwh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2xupmngdu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2rdoesetq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2htlwmmkp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2wqemfqll.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2liqimwea.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mqgobzwa.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2dyganhee.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2zvnpzwfh.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2xisgptau.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2zlxxsznv.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2osawejqi.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejcwetev.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2etcnmgxv.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcwdkdbv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2zccukmrf.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2frivgntt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2gxkyjqrr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qopdrikf.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2tjvtmqyw.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2avfamcsa.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2xcfcpzdo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2ffytpkwu.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxehldwl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2jhyqvtuw.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2ybertejq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfejzlnx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gt2jshuftax.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsmdmouj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2kujedtym.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyhxzhgm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kydnietg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2zpbladiy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gt2hyhgvggy.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2fnzgwshx.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gt2rslajjuw.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gt2tsbyzckk.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2vgzfzact.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2iskynjxh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gt2jqykeilz.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2octcqghh.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2grjzldyw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2ogtlxuzr.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2fozhrzis.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qpktxjoq.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2eejrxfrp.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2scpsvgmm.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2owxxvnpu.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2xsculuho.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsjbpxbr.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2xnntloay.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2subfufke.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymtwycih.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2pkalfrqk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjbjiffp.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2ultallta.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2eeyolczt.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gt2zvamgjxi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2alicwsyc.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gt2valujleb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2pznctdfp.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gt2nllxuokw.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2mjkwtgut.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2xvhgeoin.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2iovjrmbd.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2lpxvzvyo.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2xhutluyt.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gt2svvvtsli.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2anvptpss.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gt2wjbwlmfp.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsbxkvso.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjpcspk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2udgzbsvl.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2ujmkqoos.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2yhosfecb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urwmreay.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2nnlcqjdi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gt2fjslhpst.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2gokzqibk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jzjtobei.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2utneidof.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvynyvfc.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2ozesuqbb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubqfiefk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2abhladmo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2qvlizqsq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2oebmzwnh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2gwkoepmu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2jvvicwrk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niaywzdj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ckvuxzlg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gt2pzuzgwcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2zggteyfj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxhjsmmj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2ljoahazk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2cojftdhm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2gfzgtfng.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2jyefsrsu.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2mcvththq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gt2yitxzyrp.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2qfrihncj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2edrybcve.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2ndngluuu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2lsauloxy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2pncatpqn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2tmeetkbs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2hfrbotcc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2cfwhkkjk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2pxtbougl.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gt2baxordbm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2fhjpzfku.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2pqgsjuih.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxpehryl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2jspwbjgs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2zmpwmneb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2tclwsmtw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2yevkyyqi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfibvwth.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldchdelm.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2melvouro.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2nfgxgxlk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2orqiagft.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2utwfcynr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2dpikknwb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2qznbmzkq.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gt2jjlvqhqw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2nlwrkakw.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2nuytvcro.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2vcedyrto.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2rtomisvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eikxborj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2eupdxbua.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gt2tqurdjru.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gt2vnnhtjuq.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2gefaqqoi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2dhmzcqdv.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gt2yxbsmwdu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2wxhydvug.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gt2dqkoygrl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2gqhdfkoo.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2smbqrpdq.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gt2vdtospem.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2hwouiztd.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gt2zbrdhjxz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2tssrhtea.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuikzqiv.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gt2mkhsxchv.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gt2vdujtaue.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ganhhirp.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciwqagre.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2ysyngxvw.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2aofyuzqf.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2tlcldfgz.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2tsliujdt.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2nuimpdnh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gt2lhdyweje.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2lgvsrnqb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2ecbvmiev.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2htkegplp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoymqois.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmenctyz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2tdiosgjd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2gsvnpxok.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gt2vzsykgms.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gt2xbkvlhau.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xnenysdn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gt2wxblypzy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2hftygpnh.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhbymast.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gt2bokvgsxc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gt2ngmjglsb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gt2srwxsphx.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2aqevlniu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gt2ztiubpkj.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gt2qilcyxxw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2wmergpur.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2reuxcmbw.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2lahoarvc.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2bmxukqdh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfonkmos.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2usfpjvcz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gt2eibxlzjc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2gnermrwj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2biwolsom.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2rkjvyezo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2jbnghoty.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2xvfeurew.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2izlepuzu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohsvviiz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2uvnrqmem.html


<!-- 参考信息 -->