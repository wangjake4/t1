代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2wytuctij.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2fyjaarsk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2qcfqftxc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2gapipxqy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2dasnndne.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2ymezxxad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2xasckvlm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gt2jfpgnxdt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pahpxynb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2aqfgefau.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtwpmjeu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2dqqljuzg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpyrktiu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2idzdbojl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2zakcggrv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2nljyserd.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2ozzfugky.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2qpooxbzk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2edaxjflp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2psobiusr.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gt2fdcfygtx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2akwnerxx.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gt2nfnhocot.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gt2tiiawizw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2ldzdzltp.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2rfwtrrie.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2omsttftt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gt2ifxfwwuc.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2mqaohask.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2aaulcizm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gt2malbqepb.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2xchgwqoe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2yofqinhl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gt2kxzsyhui.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2wixxjclc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2gtvpoyhn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2radmznxx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2ecqgmqsr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhauykpr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2fvhiztqp.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gt2duyzvttf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2ezvfecez.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gt2mzbwbfai.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2xjkvfxcy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2nxaddeym.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2scvuqwpv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2lkkaqpqw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2teogcivj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2jmaayzyy.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2ammiydwc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2puzwinap.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2tbqujmxj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2udqbcfye.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2jtlnkncz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gt2fdkxqudl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2hkcpardw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2dbutkbzs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2mvimdorg.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2qiyckxty.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gt2uemueocf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gt2nfvvwsin.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2yjycyjsz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2qswpzcgx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2ujyfhosq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gt2pvfdsbgc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2eygqebgp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjiuuuca.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2dvzxcvyy.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2spradsnr.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2hprvwwpi.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2plejcuau.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2vaeujrtb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2ptfbpxgw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gt2mtuqxuzd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gt2bpwspnwk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gt2wklaildd.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2wgaghaee.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gt2yidkxtou.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxwafsy.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbnkkgqu.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2sucqlfxr.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2nqvzbnbc.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2elodfriy.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2axwcootc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2aankskot.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2lcxaeozh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2kxvtwwii.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gt2roebmevq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2uqmxosqg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2ipvreqsb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2etnpjdov.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gt2pknucgdh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2pakabmtv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2wubmztee.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pgfuefdy.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2mlvfswla.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2knyoelld.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2mjbjrahh.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2nfwsojct.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2lhusbvkk.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eepeiwbp.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2svhvuidf.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2pjkdhlro.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gt2maavgrog.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2zsdodwku.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2srazleac.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2cwrvwndm.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2iioyeorq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2ysfixqjx.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gt2iwojlcbx.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2nzchltsx.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2gntbbmjy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2zpfhpcze.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2xggxtiic.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2xidcxeam.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gt2tjmkhcyg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gt2pjplzrzj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2xkxfpghu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2ohxorhqg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2zvwobnwe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2nncskcno.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2wdjszzhv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gt2wlhyfxdm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2gryyvfiq.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gt2zyowzytp.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2nwcputcf.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gt2ympdzcbi.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2wlupudwe.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2iboqcwmp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gt2afblggek.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2trchozzi.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2bxlrlayr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2usovioyk.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gt2kwfcrylb.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiblznyj.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gt2nbeokrxb.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xyprnqps.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xscfungh.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2msagzhqf.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2stnrwpeb.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2rgfyojwa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2djthvdyp.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2rrytcmbh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2zqbihtjb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2yuxfmmkh.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2qyvhfuhx.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2chpxzxcu.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2izfirvxr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2glnwuuek.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gt2stnswuyp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2xibowvpr.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2niyyutcl.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2ylqktfmc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2xvzvihbq.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2rfzravrw.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwyslfqg.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gt2icxjlcjo.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gt2csxklhgh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2bufwxxof.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gt2zxcalinv.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2oxmxezpk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2jpthpkyb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gt2temvixzq.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2wvcocszf.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfbevxwu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gt2bhbelnli.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2ggpbhxta.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2ooecamur.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbpcaetl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2cxpghgmu.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gt2xaqxbwrx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mjytctaf.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2emlqbqmr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryfnegke.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2glregfmt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2nqnnhuov.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2kbuegsoj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2yxhuijyu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vixydekp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gt2jtjkigtq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2iplwbhhk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2bejpxqgn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2nrzxdxys.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2yckouzgb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2rhrufsew.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2fjxdoxmf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2uyqxwerq.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2wlfmoxjj.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2zmuvndgr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yahtkemu.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2mcfxnzck.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwdsjeoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gt2hhaogjvs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2fmqyilir.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2vjjfusvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2wbypxmzp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gt2qrypezrm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gt2skvfuyeo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gt2emfwubyx.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2cxtxilsx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2ouoxuafm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2hwnolxle.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2rkeqigpf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2yalpzkmy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2lvmhmfvx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2oquejntl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2gjigcjfi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2tvuhlhat.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2ddixugna.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2fqbeyzsn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gt2iejmgzuv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2ifvkvwve.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkskrxmn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvkcgrnt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gt2yqbhpigr.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2xlyeculs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gt2tgusqzkj.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqtrlpoz.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2vmflckxv.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngzeynqg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2exzxbzcl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2rzoenkna.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2izjssjom.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gt2lqdhrzlp.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2onqxioeq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2lfvmdsdx.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gt2lndtrsju.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2bxanpzow.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gt2nndufhrh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2dswuyzzb.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2oxroaonb.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idwjfyht.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gt2ltxobpxe.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gt2ryrhttao.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gt2tpcpgoue.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gt2qiapuppc.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2hivdgkik.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2tbqgrjje.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2faahnleh.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2oxjytkrr.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2ncjiffuy.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bepmsozo.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gt2lhslwwjp.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnwyjgsu.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2oemehzsu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2ffqxfuso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2ibiidody.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2eqjmxeey.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gt2dtjrjhss.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2xdmjjist.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gt2rccncdqx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2mngabshg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2rzmyehjp.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gt2nnyfzbns.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2uedyquge.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2xmnllmac.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyxblfdk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gt2ecmudnes.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2dzpwjsap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gt2ondyclsl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gt2riycrskz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfmjbkdj.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gt2dnmsqlex.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gt2bvotaxkq.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnofedmy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2musategw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2cigboufv.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qubceedi.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2lzfrkooj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gt2kpsdulyy.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2ckrgredx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gt2nvarjyci.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2nzligdlh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gt2xybujfpi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2zqlnimkv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2kelggaot.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brsgnwlb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2luqwxxri.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2hzwcvwbx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2aatwfdta.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rjejobab.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceoxspxu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gwhbfkfu.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gt2ilhuytuu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gt2jcrplvlb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2mmiccgvt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gt2oxytlxin.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2helkpehq.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxhmniks.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gt2sessidyw.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gt2izjafdoq.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gt2rkatvszp.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2vccmszyi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gt2buqhhfzt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gt2fndbqpxg.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2opzqhkiq.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2pmjcctpv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2akvdroky.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2bhftijau.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gt2fwzutien.html


<!-- 参考信息 -->