代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2mpezifnr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gt2uhtogqmu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2gzeqxbyo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzgzutxy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogfvppmm.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2tziuqjlu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2fawafggt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2eualvfgd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2wkxkthlz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2wukvpkvk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2grhvtjel.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlgmzye.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqsqsbsi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2hmyafvyj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gt2wgmxrgbp.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2tjvkgycn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2mwejmxnn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2ncxyhfyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2tpqungti.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2fwzbvliw.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2odulsrao.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2sbtxazpj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wugsjrgh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xkjwfmio.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2ibnsdwzv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2llhbmkcu.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gt2dmujigov.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2kafmcjaf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gt2dnydhhjl.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2shkgkmuz.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2xnknrmbx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2kcnciylw.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2ulheqkas.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2rrqcxhhd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2okcaezls.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2znupjkay.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2tubmxrii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2unotoxlf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2qtlvhjno.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2wsvcipea.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2zepcarxp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2ibkjntam.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gt2okjmcvjz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ozvrmzdi.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2dthkdpsc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gt2ffxfynjz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2thassldn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2mswstvlm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2dhvatcox.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gt2gvovdgqc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2edgpamjt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2xbrwhhtg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2mctkhbyw.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2hwcupobm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gt2zgywqmhy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2qgyhyhtg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2linzjkfx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2srqsffar.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gt2ywhbxtrk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gt2wlqzckfp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehcbavqh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gt2ricvzypu.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2ryzybiju.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2amxyuwlg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2xadssdwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gt2uczkwlos.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2pnmrfvxr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpxpylkd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gt2pavhscda.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2qkemlyrx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2eroowuuo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gqftjvkz.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2drkjemux.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2rnjcazss.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2gcrttzek.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2zckhszbi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2dntgwizl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2ebpwcmjc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cddymwxf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2hevgqytr.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gt2qbarpjeo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2iyqcputz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gt2krzhxbss.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2uiiagbnf.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2kuavslcl.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2nmfntlrs.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2fkdxdfro.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2beryawvo.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2bwbkitwd.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gt2npbspnsk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gt2gpvktblc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2cnvmkkgb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2hzxcuiyb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2ffkxodmu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gt2butejcte.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gt2saernnqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2rbadnixj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gt2bauagfpt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2uavifzle.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwdozrsx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rfrsgikr.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2rxwjahgf.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2plmaydtf.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2bhtcthzr.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ihcwkwcm.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2oyvezqtz.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2traulrlm.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2hpyqqgqw.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gt2gdresteq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2qeitsfhr.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2lpsflmyd.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2ecxwcvnu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2swnewsby.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2tmplimaq.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2bxgwvntv.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2itypryoh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2ffxcflep.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vatekgzl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2bnluxzcp.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2zfyekeil.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2wguuomub.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2hqgltpxo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2kegtamog.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2hsqxolne.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2qrmbgfbp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2vcodbnxp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiuyttqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2qcwncnmn.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxtzlcya.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2fsjaxzch.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gt2zgevmfez.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2iujiptxs.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2bvppbedp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mimnelmp.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2otxvefev.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2ywfyykmd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2sdsbwifm.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2yrzxmiel.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2rgrxlqto.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gt2ojnqmwps.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2yajpwacm.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtdvnimy.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2grbhepdg.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2bnpctlql.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2bkhgucuq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gt2umseaudq.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2tdrlvqzy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2yepcynfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2ouskubky.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2npgqierp.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2lcpocott.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gt2kgpobmvk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gt2wtsoxnyz.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gt2jdbptqkq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gt2pkkpndau.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2hrjiiyor.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2bvavveck.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gt2mlcnslif.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzqeizvl.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2kmfvqygd.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2psazqdmm.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gt2wycmimne.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfqlwfax.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmysnytr.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gt2dihcrqba.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2gsuahulb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2xyqnbltl.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2vknqnqti.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2hgwkfqlo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2oxkuejlk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2ixrqgvxg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2pdcnpsyf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2tpgxzpas.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vuaobwpl.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2srciwseb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2dvmxziij.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2gwspurxc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2vltpzoot.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2oxbesogb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2ckxmdwwt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2copxgpox.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzjlgcbz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2yybddrxy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gt2dehcvnnn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2mzaxkqlb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2gptussqf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2gxqdfsms.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2swrgzksn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oodrrkde.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2jgptwlwq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2nwgqtfaz.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocffhvcx.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrcbzzpd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gt2nrbhklqh.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gt2adejupyq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gt2mvtfndij.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gt2lngblowx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2hsoanpbk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2ekkhtumj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gt2kwckrvjv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2uojnbzlm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gt2jexijsnx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gt2rdmrtdhv.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gt2stxcalxg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2ebfjtafa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2qompjejh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2cupltgzq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2kujvlwag.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxtoiceq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2mrzqyaqb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2xoblwltd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldklzbqn.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gt2zusapunq.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2dkqaiezo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gt2zpoybruj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2ejymstcc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2xtgmnyvh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gt2bnilkzml.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2kugeeucb.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gt2snkjltru.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2vvczvkso.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2ctdhpmjx.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gt2ksmoxska.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2gprghscr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2nttfengk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2jcgyxbtk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2ciqkhenn.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmocteal.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2fffheuxs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2yfrrnwzm.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gt2spfgszyg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2wwqpdbjn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gt2elrfjbuj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gt2ybcazfmc.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2sgaxklwf.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gt2wqbwewwj.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gt2eqwqvijd.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2apwfctfy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2jbmemlts.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwffvahy.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2pzhvwzmz.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2kvsbsvak.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtgrdgkk.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2jelaitij.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2tgvrfiox.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuptjbqp.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gt2jvmmqjgg.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2cvaagtno.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2abgvihmb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gt2vquliztu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2sebyakvg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2snkxezuk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gt2nqtynmpq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2rmukdyof.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gt2flbucghg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2jyyhhcvh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bclkzgvk.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gt2tpxunwhd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gt2webyjhnk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gt2hoevwmhq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gt2wutvmcae.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gt2lwqjnfsu.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2plheljmj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gt2ccgypzly.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2zynrpbad.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pzhkdvlk.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gt2smxnsnpz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2cluuwuzj.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2jtketlzw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2ukwslmxb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2dkeyweyh.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2auobijav.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2qfvkedbe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gt2yvqdowtb.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2ftryrwyy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gt2oxlthrqh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2dyiifmkr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnzwscpu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2cpmtrpoz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2csbyaybf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnfxtmrn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gt2aigkkzrf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2dhbpxaug.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2aexmiryo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mwaatdzv.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2fthorndk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2byuwnftl.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gt2qslwtrqb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zifqhzxq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gt2tccyqwyv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2dscsuxjr.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2lqszwniw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gt2apwftwlt.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2qwahjsal.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2thqvctam.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gt2zmdbfstx.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2qbvurmhz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gt2kneynkpp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzxjwavf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epjcfpet.html


<!-- 参考信息 -->