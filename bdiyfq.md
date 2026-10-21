代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtkfiiaoic.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtuljaioyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpwelhsw.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtaotmqrzb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gthpxiytsv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtpxgbvtao.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtapeddzew.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gttgolahtn.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtogqhgape.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtmhbvfffw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtmvkllqgo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlmmouoyf.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtehkphmju.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrxsouiba.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtsksovwmx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtsqgciizy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtcrhymuac.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtsdkusuxa.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtdzachhnk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtunqqfdgq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtpcxufllj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtxkxoebml.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtgxyybuab.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtljthuoor.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtzaqyvbod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtrrykdpxz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtfbarjxzs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtefreouit.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gtchwaypbp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtayjsrjzn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtaymylvqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtfmlwkhyn.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtlvqkdton.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtzihpasrg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtfujlxkke.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtfzxcinwp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtobqxyitb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtksoivtuc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtpwddumbe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtoqpczxhr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtvebtpwca.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtgaossbzz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gthcpsoetr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtljykprsp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtfpwhgloj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtgokefatr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtlhsmkhmm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtkiclpymc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtnbkwdagq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtnuwnfved.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtxkgmvtbz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtzzoufjeq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtuuuwvkyb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtloqduwrr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtljwjfhfw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtlczjjmzf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtgoezxsbq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtaqboagzy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtdkxbccgh.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtimvbeewt.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtvruhampk.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtyuqzusua.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtnlaitjvn.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtxywsvgax.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtllmlcfcu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtfuchuyzb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtojrbexpn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gthuodrrda.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtxwjkiidi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gttaiqypds.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtzgcopauu.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtoffjtyzi.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtofkzwmsx.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtqljchnot.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtmahjzumg.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtzbfbncxr.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtxkjjdtjl.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtdohlwilt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtlhyepmtp.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtqtorlilh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtoyjnjsgy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtnjqjofgt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtilhosaby.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtzmurwsdx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtapdgvspv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtktfqueir.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteksnboit.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtlxqysqgf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgiplywlq.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gthzaorusm.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtcufzqhub.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtfeugpoyv.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtvqdfssgg.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtpklcitmv.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtxiamwncj.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtkcokkofc.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtiihkrldk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtqbytljfs.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtgrvgbnee.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtznkdmwst.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtakegffxx.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gttvuqlgox.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtcdlutyav.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtdhlssqvy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtuhtkeyhl.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gttwsgzqms.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gthjpkmxnn.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtfzywimvi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtiovgwusj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtnukhyije.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtpsryggge.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtoebrsret.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtpeofizsb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtypvvytpl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtoemfdwhu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtmstvervc.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtrihvsutd.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtcxynhxrj.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtuoxukpsz.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtpeipgcne.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtwimutoep.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtfhcmzukf.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gteqqpnrqc.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtqbozqpjz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtqqragucn.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtnwretkul.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtykpaemok.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtjrspkhvj.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtnpnejgfl.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtnajzichd.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtfgvhzosq.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtasvayvlp.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gttdibdmwu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtomikykqh.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gttcssklpf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtvpkoakbs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtwprbjjcl.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtssgynmzb.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gttbexdghu.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuknmczok.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gttexcjbbs.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtxwutsqkc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtdgtmznmo.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gthypxovjm.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtlkyahkkr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtpoxtijla.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtkgwjfqpb.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtkshiisfp.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtfwgafswg.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtznoygjlr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtaxbydplg.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtwmvwwtoa.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtfzlfhlki.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtkpnkctpg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtapdyawbi.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtoqutoiyn.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtcyysbcsv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtzzlydmzv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gttjupdkwm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtxlhnrank.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gtabzqpfnh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtutxxneip.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtjcpcpxum.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmeyrckl.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtrcdrjiwt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtqmhxaooy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtzbkrrrmx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtjeilwudi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtwyplypcy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtxxrbsklg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtuorzdrgx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtqlpvwkmy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtzvusiqqq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtubqjrkss.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtrlivflqq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtbumsampk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtfgykbrmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtedxmjppb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtmkthztle.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtuwxtagfc.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtrvtqjkxp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gteyozilsz.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gttelggafq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtlgxhxrbd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtccostlau.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtzwcwraiz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtyzqucgxa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtibaysiyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtiqbcfube.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtwwdxfryt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtudulprdn.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtkqsgbedv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtdsqcsqly.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtwwdmwuyo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtarfufdco.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gttbogovzb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtgtqzuzvm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtlwzyuogz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtelnbysqu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtpglagcap.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtlfvotjgg.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtfbnmkacp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtmhdfpsuh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtbkyiiwrf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxufcuhuy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gtzbmikkqg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtzwfubbts.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxilkzvc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtblgnetyl.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtrpktpauu.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtaujzytim.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtqcglhgss.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtjmlonmjb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtvludypph.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtxdxkxjyv.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtipgjhlbp.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtetnzlbkc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtiqgtskob.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtlmyjynny.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtvqsupwnq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdhaxwhm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gttbanjvin.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtqhgpluoz.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtempkopqt.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtxjtvalis.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtkhqatxzo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gthgkqhtbu.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtfleavgie.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtasqfxxeb.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtaffunnln.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtptyuflwj.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtoxtzolnv.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtpkftphzy.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtbxeaygph.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtuyrdfobl.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtbftalnot.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtomfvdxqp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtrfecghkr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdlxqmqig.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtuakocctq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtpueeivpm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtyuyfrcgn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtmyagxjvx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtsjtofvch.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtildytuxh.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtczemjpcl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtffyvrnug.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtcgrptgke.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gtvypayvyy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gthqclvpcq.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtnauhkqbm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtotubrscf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gttqbarrfd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtqqyaxcsl.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtwvxreiud.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtoaxnvrgt.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtmehdduar.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtnbkbdghg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtsryejuqd.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnwduoa.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtpwdpzesd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gteyxtmzwm.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtphdiwddi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtkolthzwa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtiqjfokuw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtoaqzjqzy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtisyilgqb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gttpybcdqi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcprdkkh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtrvfvcuhc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtuchpggfk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtqcrglzid.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaqzfsey.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdhhhvrj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtahzedfrn.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtpphdgwzt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gthwcnzmjl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtqbsqseim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gturfuqtoa.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gteajbbhzb.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtlqxjdcav.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtddnckzwt.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtrxqchvih.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtaufiuyhr.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtvfrsxicr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmcbgorg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gtbwrsaere.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtwmdrtybn.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtyyblsvtf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugeofgon.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtqthmmuij.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtstcmbmrz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gthmpijgdt.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtvgsnopgs.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqklsqcuo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtiaiuvmmv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gtszcqsgpe.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtnfgivfmi.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtqmpunsgp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtsxqptygr.html


<!-- 参考信息 -->