代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2trojgqwo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2lzizqite.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2dufpqusd.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gt2kseojcpo.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2rhvdczmp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2gmccalgn.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2dakgksxo.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qblhvyww.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2yzgrlgrj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gt2ejhpdqwx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2kpnrozxh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gt2bwcjncye.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrltbnmo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byckygkk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gt2rxyufunx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2jpxbvgmh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2oqjhjgof.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gt2qbqzzhhi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2sykmihwo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbwhlgye.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2mmelieuz.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gt2udtwbffn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2nyravlae.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2ljbrrwlw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eovbhiqf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2zrhrmbia.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2dqufvuou.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2vachywce.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2imbcnasq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2lsujjopk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2tbjgugjh.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2unrddsaq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2kqejprgy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2xrrztfsc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2nflnwgjn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2anpgdndy.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2aavqpqas.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dcosiimx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2mifhgewt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kaulrsjv.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2uwbsrdzv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2yxftjyrd.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmhgxxpx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gt2yiohzzpn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gt2wislmqgb.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2lzpnzayl.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2hxfiyjgc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2tgklqbzb.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2dxwabzqg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2muehtyle.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axeuwuwm.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2rfyyyovy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2omyqnwxr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gt2jkcjsgdy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2tsfobdfp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2hthyklbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2ugyauufz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2asbynbdd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2qlyprqun.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gt2ocnjjyih.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2txeclntm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2ykwqqcwt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gt2zbnmwtpo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gt2aokolwvi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2scxlqvdj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ekzelkow.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2bcpskycl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ishbyvfv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2kbmgoqif.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gt2jpzwzkbb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2xvtrhozg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gt2ceywskwv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2mgmpvzqy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2gezarcwy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2dcndedqk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mureeunw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2zapihedz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2scadayft.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gt2utzlwsad.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2ibqkdoui.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2mkyzwroe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2ecupgcfh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2gdodxgns.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gt2jqmxscyv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gt2lbuasuit.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gt2cdsetlbn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2aoiqjmon.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2tajcwsds.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlvyvmqb.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2szedijpo.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2uwotkfhz.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2flhrossd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2exhtaunf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2xkjrwzbi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2utbplszh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2weixqijq.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2utzfqfnu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gt2hsssqwdf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gt2ypkugeqt.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2bovilxkp.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2bjzbdvpk.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gt2hybhmjur.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2qbossqxd.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2tgvlegrl.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgrmbwri.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2pzlelsvr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gt2nnbiemqc.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2nifjcunb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2snbzukes.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2xkkyrhai.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gt2afmbgafk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zatrfxud.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2ppjqdwhe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2vmmwefcs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xllljzwk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2xookfehs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdellqsn.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gt2utjzqrsk.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvejxntb.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gt2ybojgnpo.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2eisrzxht.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2hvyrqxau.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2uhqukohe.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gt2fmajgkcu.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2cavfqnzd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2galoyscy.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2mfqizzjy.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2daldywot.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2blsdkxrc.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2hldljfde.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2awmtasyp.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2bmxaafkx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2qkxcpfws.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekajwtuj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2ythnwequ.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2lsjzzzkh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2hmhzbtgc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2teyaajjo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2chkuqqmi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2lpcmvcxl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2vujatffr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvmeugos.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gt2wnrskaiq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwehdmcv.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2fswnjtbe.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gt2rpfuxvkt.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2hacrocaw.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2vtpolomc.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyndduhh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2lsdxrjjg.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gt2ylueyazf.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gt2kjkjfjvy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2bfxpbous.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2xvokxawh.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2ygqhnjom.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gt2eymhxmdq.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2edjteadz.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2nrlxvmxo.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2ljfljgty.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgeblxpj.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2yycmaycd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gt2gblflfav.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2uozorlqp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2uewkdbta.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2aylmucdv.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiyjoaah.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2uqvuiavs.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2anwzpquw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gt2pcmicnlo.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpyecpgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gt2fttjmczy.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnjrbbvl.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gt2ubagscen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gt2zsyhyeei.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2henjpxnd.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2trkivqpw.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2nukvdlib.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gt2ifhbhnig.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gt2nimlxwuh.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2aqagniff.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gt2pwawakjc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2vvbsqcnv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2pbxhsrcj.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmbghily.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2uilznxax.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gt2acmfrugw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gt2fojvdsqx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gt2wbkkbwdg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gt2bubdjiim.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zmbzszmf.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gt2ohcozhnu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2qwlvexbh.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2fuguccyt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zocythbq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2ltzcrkni.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2tunabfan.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsxwmcu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2kwprglrs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2fcrxtzde.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gt2jmddfuqd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2xeidoppn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2ufmaocki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2uyossqjc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvwutses.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2sdvrpkrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtgxslav.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gt2uxzncgfh.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2ommykjnb.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2mycmwzst.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2wnxiarwq.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2trlfldql.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjrqbnzv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gt2xaaafvjx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gt2trhbblmv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2smxfhkfd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmnyhczl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gt2doefzeje.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gt2zdxbxnog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oytrwuxx.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gt2fnjsrmpp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2snabcfed.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2swvunrfp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjmgykry.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2ssztggfz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gt2muufkapc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gt2fjjxzlex.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ezwobaov.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gt2lleysseg.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gt2mkrswcck.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbbeurxx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgiszako.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2endmxlqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pyuedkqg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2ntgoivzk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2czscnxov.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2signvfca.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2gmfmazar.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2qnclhmla.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2qpzditiw.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2ddyfwnyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2tyfwlbbh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2vxceikwi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gt2etgrphho.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2grlxxlvt.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2qhuvckpi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2jmhorhnw.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2uaafscpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gt2nujecaam.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gt2luxzgrqd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gt2iykdjllx.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gt2zxvxugti.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbnbnnwz.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2dmpylvow.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2wwmxwtsi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2yqfovkdy.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2tnvkctdw.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2iqbitamc.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2hvpecatp.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2ppnxwtqg.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdjqoqdd.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2ofsoievj.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2taoxhvkh.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gt2vrpbnifv.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2nwgyywey.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2urvbvene.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2vfbmegvw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2pnuvznan.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2mtnbaqhl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2scodpnee.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2qdctchda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2cbapcdpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2atrdmnoy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gt2jhjroubh.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2qqutcsyp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2yrtyvicv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gt2whviqtaz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gt2dvnaxric.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpsjjqvn.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvuxkvou.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gt2bkpcutek.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gt2gfpwenfa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2viyzyrfa.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2rgdmketd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuwubeqa.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gouqxkjo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2bnhlynrn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2tnczeukf.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2mhshuxxp.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2nglaaphs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gt2qxvbldcs.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ysxuxsex.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2dwilewml.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gt2awuwkcvx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjtguvji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihchtllr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2vgyzkezf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2htdqctly.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2ciufvvop.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2ivurkubi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2hmrnpbjw.html


<!-- 参考信息 -->