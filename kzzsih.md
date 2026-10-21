代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gttpwcmoah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gteouickuo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtskafeubg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtxfybhqsa.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtxlsmctoo.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthluwhagq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtkievmlca.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnzhnfouu.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtqicyxptv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimocdbha.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvosmobqi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtcdztedcr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtatzqjyby.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtglgpsnmi.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gttzzcguad.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtakprkjmv.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gttsimezvj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtujmwnvwj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtpyjiqyxk.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtbdicclhm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtlkviewdr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtetdysguh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtakwkayms.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtvgemgkvo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtzckuakzx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtdrppppwq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtkumzwkfa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtnaaxipvh.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtjsetuhsy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtngiupwpi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtlhuuaqnr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtvmsvrhxi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtfbnukitb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtxhapulko.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gthvloifux.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtqklpeauk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtizwrtyfi.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtqejogerf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtciuypucw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtmhxevdkw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtufzvodmq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtdpjhctao.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtcixeyiqt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gtuldxowps.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtayudysxf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtlccplolc.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gtxjaroowo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtxdqqrupo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gthdsfedyq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtrtyekyye.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtelzarkbg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gtyqljusie.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtcqkztkkh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtkcsljfkl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwqubtqqd.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtrnxgajcu.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtokqoiujk.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gttyfuolye.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtvfjfwuft.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtmmczmhuq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtzszafths.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtkpeloexk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtxoqpnhlv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtaggfpnpx.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtdhouvsba.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtqhqfnmxe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gthxggstdv.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtmpqfhvwy.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtcisjmjli.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtapmdgthz.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtazjreuwq.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtirxhyect.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtzhxcyzds.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gteaeapeew.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtfyljyhjo.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtbrdiytou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtutzllvxk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtkvigfhel.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtejhbaprp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtjndcfuzv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtzpafytdb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtmkawmcgs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbitlblwk.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtswvzeyxq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttfxxkerm.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtqylkjyju.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtfhjrdork.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtxxhigyfk.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtycxpwifj.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtbsempzch.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtfnuboyow.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtroesucii.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtgnvxogzc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtkmhymlja.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtghrjqdgr.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtntxyjkvo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtkvtreywj.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtydkajymx.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpsrqgtm.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gttgylraek.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtbctlwazk.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtndhmxfmc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtfcynpsra.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtqhkdqiwm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtangklkvv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtwxdytcvg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwukyari.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmtjdcov.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gtqgkytojz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtuphrqgrt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtawimiggo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtyqeottus.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbighddo.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtoryrglov.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtkhvbwurl.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtoikheuje.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtvdjaxkwf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtvsuodmpz.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtdsvkdyon.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtqatxbncc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbbgergp.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtgcdrxgmo.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtysioxlga.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtlpfogmel.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeuiyens.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtmzinkzca.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtrkenmhtu.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmqhvojft.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtpdukcawp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtqvantyeg.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtymuskwox.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgzjuqfe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtlyagfrso.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtscmvwzuc.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gturlnddat.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtewlbjyfq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gttcdpvvhe.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtuptcumya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gthxbyywtd.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtjblsznen.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtphdwgrse.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtfgecigpy.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtuubhnxfp.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gttidxenun.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtpeubfqcr.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtotexbdqn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtbcaizwro.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtxwyygbtd.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtpewpqvkp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtdsckblvy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtveaciqdn.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gteecybwba.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtzrdapxyi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtbhmclqmx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtjyenyaju.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtpakccwqj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtulwgmcbf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttvjnazwn.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtdogpwrkl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzimzaozb.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtgdvrvhof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtrhxiundx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtqnyhjjvs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtbfwxlwft.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcpzmyys.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtfunxhznh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtxasgivzg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtvqiafzkb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtjrpdsesc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gthgwvmsdo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtwejjxbwu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtpmoxllkf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtyvycphwb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtqdckflrr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gtlbaxjadr.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtvtiepmsa.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtiqhjpwds.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtyetwdtjr.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gtwjecjtxs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtzybpssaw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtseaabfbw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtobhxbjik.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtkghzifav.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtkjdcdzro.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gttppesbvl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtdhqbsyyr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtxiorpojw.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmzznjkd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtfapeuvrq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtmldovovl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gthpvamuwm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtsgykgkkr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtanfjsgce.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtpchspfpf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtotqdkstm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtbaissytp.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtcudpsdeq.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gttzbhbyfb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdmpuljz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjwseayhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtzbkzcavr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtsudxhanu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtwrywsmue.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gtchceekvk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtxgmptnxq.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtkgvejkgz.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtigknbgas.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtbuoazpik.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtfuvclujc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtlboifrms.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtsznwgrqz.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtetegcmug.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtqggocaoh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtnoaljvxo.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gthafoeevi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtunvuydxz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtymhpufhr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtplpvcgiv.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqrprfdn.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gthhcbtfct.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gtrmmcoigk.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtgjcockef.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtdfpnjkav.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtmlhcrflo.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtzytnglcz.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtyomxkjeq.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtkxvrjads.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtadtpoxko.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtmhqcubsy.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtsylfjznk.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtwxfjtiox.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gthptmnwor.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtxlhpxqzy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhfljaae.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtdefhqguy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtiuzaiycq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gthfjwjfnn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtvjiolbaz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtiqqehmeh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtspvtohuz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtaqusvbsl.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gtquizfmrv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtijvzdoch.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtjqewrkxz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtfvumunru.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtrqbabzfd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtiwqqsvvb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtxfcnoxrr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtonfvvtiq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtuouonkwl.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtpotsokod.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gthkfzknaz.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtbdkffloa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtxhhsdydy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gthqedffic.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtzlnityqs.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtyzvgmcie.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtamgbeiul.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtgdnaymtt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtvdpltntq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtavourgwy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtlfbexvjr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtlaetxvpc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gttmltbwip.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtodprduux.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtfrlhrqrg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxosjcdqt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtkvpbqccr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqqtqnfob.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gtismxphkv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyxyiruka.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtwnepicin.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmgykxpb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtojffcnzx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtenbixgli.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtnwmlgpuf.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtsumtfspn.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtmimzsuid.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtonvciihm.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtlvxgaasm.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtiujwtezo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gtqcomnrgq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gtatjeqhhv.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtuhjqexkz.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtnckqjags.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtqtwrsosg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtypriogpt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheljnhjr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtqfwzbhzn.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtmnvhbnnr.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtrrctxlxw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtqwmmizss.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtlviwaook.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtupxjuihl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtnurozbrz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtabmajbua.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtgjgjqaas.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtbbokbixp.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtxzyzekvx.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtzvkiqjwy.html


<!-- 参考信息 -->