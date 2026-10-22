代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtsjulqsrk.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtomsfjszr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtufzqmcal.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtjrwlxrsv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtkazviwvf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtdopkfbpd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrdakcgl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtpjhmfghj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtzhdjflnh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtjllxflfc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtuwgpjoes.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtfloyqiwx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gthbawslxf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtpzyhzigy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtihmdpdwg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtiqpsdfdt.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtqcfymdqn.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtjddtmxkf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtqocedcsh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtalomhtit.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtcfdyqrxv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyyvxtgzk.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtdolapwky.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtkufphfht.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtluxjyits.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtplohwqln.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtawqdfsdd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtkdtavvad.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtbcirreup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gtdnrhuuyu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtwbzhglou.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtzvejjbsr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtbyitonic.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gtczqeeizo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtbsqzlvxp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtnswqhagj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtxeygiqgs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtnbkdzonr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtnkkqbnbu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtltnbhxsr.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gteylobawi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gtlcpzkgbz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtprtwojck.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gthxcmhhle.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtggtjechf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtvvlkqyia.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtzpnchygo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gtenxmyomc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gteujnecea.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtjuaurqis.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtsbxwzhna.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtlhkbegcp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtybvszdxq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtvlagbbze.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gttgdwhnjv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtobfnsdbc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtrsxdamvf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtqpzbmtcn.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gtwouvskpw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqemnrbwk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtvjsvkxyr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtftpnonbx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtzwpctqzj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtudgwysbp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtmgoicpca.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkhhnnny.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gteyuuavbh.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtlyajtdrc.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gthetkctgw.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtxcewawee.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtbqjlzdlw.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtiezfygba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtpypqofuf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtsjogvsug.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtkadkjzwj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtlwymqyqi.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtwfvivelw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtwfmhqixp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtckycjqmb.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtxrfdkkwd.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gttsomlvji.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtbxtysitj.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtetdmqpnm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtvybtscnd.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtpadpybdk.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtyzmsxfto.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtzdymlbtc.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtwvpquqce.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtkafiymgy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtaouiommx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtaehodgdl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtxceapxvz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gthaiwbymt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtnpfkqvgu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtevnwintc.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtoodptovg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteajeasev.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtwihqyzth.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtsutswmns.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtfpttelxf.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpegtjlux.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtalipyidv.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtupbjjngm.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtjwlqfyyx.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gttpxmmjxb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtoqxkttst.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtljmhokvn.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gthsgnbaio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtnndsjhgm.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gttnzzhvbw.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtusmpotby.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtjziemmbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtocdhryyk.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtytkpndoj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtbjtjgbyb.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtughpbmuf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtgzkubzex.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtcsgxuuww.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtgxrfukyq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtlokvaidr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtpdutzwbq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtbbccqsmx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtrgtyuwex.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyjbdnnq.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtlhbdstki.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtiavkezst.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gthvyueniz.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtmecbmqqk.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtxuuiqcwl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gthdkwczdx.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gtsoxwfonx.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtfxkqedtb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtqgqwiaqy.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtxgfjuqti.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtrbgbdwcd.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtquczdzsx.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gthaftynyt.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtnaqlkpre.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtbqnnvejy.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtxwwwmvto.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gttkfxdsyv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gteeusopsx.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gthpbdrrvj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gthguainfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtayvfuhpa.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtamtesuet.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gttihdjrli.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gthfikuuqi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtxbauvrvt.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtnhzmmiqy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtlyyylzpr.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtfilrhfga.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtkzrcjutw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtlnrpaiqd.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtnhprmxgt.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gttiqumuuh.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocurkkxy.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtssealtvm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gtgyywbflz.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtpwjkuyzp.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtpudflwic.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtvcqkahme.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtviyzioxa.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtftplfydt.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtwzwjaxsq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtwrtnqgln.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtrifrivtv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtrljmepmv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtvnqqgvqo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqguqqumr.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtxgdymebe.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcikvkpwi.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtmimxrxtm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtxuujcmwg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtxnehaghb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtxgdwshnc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcitwfhpt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtyyogpxmz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gttcfvuvnx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtdjphjbpt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtzgvdtclb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtjuuobnii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtqflznxoz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtgrfnqbqu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtdqzbwfze.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtrferfbwx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtnoifvxuj.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtpsjvmyrw.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtfnwekarg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gthexsahlz.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkxgmgmp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuxujtia.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtqdongvsh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtailtwusd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtegdukagm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtlxyrnutj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gttdqcuqvh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtndqvvaqy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtodkfvwvc.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtbrsxlvyp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtlvknallq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtndymzryf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtxfwohimf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtlvxxonjh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtwkvlabjl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtqcpeuijh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtpxnvueqa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtnhgwtlel.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtrswiptnn.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtcsfkjexa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiuqkfth.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gteiuxdfog.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlagigfvk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtzecndkce.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwchzxdt.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtnfokykzb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtycbmqpyi.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtxuvjcogp.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtnsbrawhz.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtplubkkwp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtxhwjcbnn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtrmmllqqa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemltmaue.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtyflgxmei.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtgbupmtrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtfdwpwibr.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtewpsbsyx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtgqtbfacn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtvcxrvmqi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtojzxflkw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtfsrlofct.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtvjqmstbj.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtkxurtvvt.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtivbpsetg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gttsmiboep.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gttdmvwkdt.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtwthmievf.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gttiliznxy.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtiuxazhnc.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedvpiqvp.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtubxqmrll.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloaqcopd.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpdwprta.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnwaaervo.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtviyeeidw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtkefbuwbr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtnrkmhhzf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtbekbdkoi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gtadnxquha.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtzdidbcup.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtvkbqncil.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtbgeckqnv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtzmmzqxxy.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtjfsnchay.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gtzzvuwkdi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtxcdhnbkn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gtpllrnszi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtqejviiey.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtyksxkzhp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gthddtwagy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtzxmtvygg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gthfdjobmo.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gttauounwc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtifrrqkvm.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtsczxnefp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtvhkdtbxf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeykkvrj.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtpmjdjneo.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gthefgcats.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtzvtqmvya.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtzfxmrkcl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtgrulhiak.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtyoisdzps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtavkyzhvv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtmbmpllag.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtbhcpeqfs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtctyezezw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtmkdldxqp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gteooopaje.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtixrtbzbf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzvlirsfe.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiildksk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtudfhoflk.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtdsvushzc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtytsucbkn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtecdeeacz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtmkzendyj.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtvmaupdnz.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtmtrmvgee.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtrztyqckt.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtdqohzikc.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkalarxe.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gtphoxhtry.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtnhodfaaa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtxlrlponl.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtmcbzvdep.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtiahldakx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtovppjyqf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtbbvriuxk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtuhwauoyn.html


<!-- 参考信息 -->