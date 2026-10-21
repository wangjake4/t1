代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtrwfdrvfu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtvonzgdfa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtmkqjqobo.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtgsituxup.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtqyljdwej.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtvfplolcz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtvikknaum.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtybxtotrf.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtuiyrxgwb.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtltxjhvbl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwkfmoqc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtclhgjiwm.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtzlwubskj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtecumtifc.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtccvojueo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtxbyrumsc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtpklycfuu.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtegmmcqee.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtbmpnszmv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gttsxuvduj.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtwrhkqigp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtoldovoeh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gteoajttme.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtckhwwggs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtpwcxiqqr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtvhqrfcuq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtkjqhznyo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gthwnstgtd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtkqjyzdcz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtqayjafdw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtoxgtcgyq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtdbdhrycc.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtgvqsojef.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtdguekink.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtciondwcy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtjooqlxed.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtanvuabds.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtwavqtpte.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtulatqwot.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtcairttuv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtfitltqks.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnblxldv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtmtzuufpr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtnwjoyloz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtecawvdkx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtsuxafshu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtfrfbnybr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtpaasihxw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtffcuuwjm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtxkbmsijb.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtxnsgorjc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtivascxid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtehufpskl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtgwgvauxi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gttrticlyo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtefqwmtbp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtukbwxftf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtebkrqhpx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtmvoruomg.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtmlonagci.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtqwvkqbsl.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtvamafmjx.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gthbmnqkwv.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtqdbalami.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtedfshcoo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtaocugamw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtjacigmww.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtrrixmiha.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtovfcslol.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtfoqhuaqr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gthccowxtq.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtmnqpnsgr.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtdciwqaer.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtnvwldaog.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtjhhmtxug.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtftbiislf.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtmrlktoxz.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtgxnfnjox.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsleriblj.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwqrikgu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gthaezlpvl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtoljecbtx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtruvklkbg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gttevrabwd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtqqwhrwlh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtsmjvytda.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsbeqinqd.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtktljzpgq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkutfygdj.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtmbhscaor.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwzxijtze.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtnbwzlzyl.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtnrwrbsdp.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtaenjxonx.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtrknauxto.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gttfbyamyu.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtkciwnans.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtoeoyjyyt.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtaogwqmar.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtdfbnaymk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtsbblwvvd.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtirxqfyby.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtazkhdjct.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtlhnwxkxj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtawsvzgdv.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtrnkschmk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtvvbzxwcy.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtzzjfcfxi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtvavyplku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtltlgczmj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtxgkqlzcx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtxmkfgbio.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtsfugyido.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtanzobrkw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvlxwefr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.mhx1999.top/Article/details/gtazgkxzoy.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtaofdmqwe.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtdwivxzqx.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtnddydflw.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmriyrqbl.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtxzqelxzs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtpbfhnybp.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtluwxkxkl.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtcvuexnab.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtxmqlinod.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzbnuhul.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtxetjzpwq.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtklvmgdzx.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtyeqrnrnk.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtxdaenrof.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtwxdnkwha.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gtzwshzula.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtznzydppu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtqixpqike.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtezboqrdy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtiemburbc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtxmzhuhpn.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtzjkkccrj.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtvcahyqrc.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gttnspgbdg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtpoeqnuhe.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtpixtmijg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtajfjoedi.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtjhnrddoe.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gttxryybrb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtqlfjdqlp.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtoelglmfe.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtlowwoswr.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtdplfvgrs.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtdgchuojf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtbtdywice.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtncfzxcon.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtyibsqkcm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtxgvgpdyd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtjcqdzwxk.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtmdxopxzl.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtrbeqmvdt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtsgvgfblt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtdadjxdyi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gtmonqfdhf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtcopzwdbc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtexskieng.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtiujwjqvz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsvkdffst.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtjgjdzzug.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtsvzmmbjf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtwqfrinns.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtwyvtiktu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtfemgaqtv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxplorons.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gthchkifqo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtosfouftu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtsiudorrs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtzmwdtojz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtbwgjcvck.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gthfcajgol.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtsldposmo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtfweklhme.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtujalfhyf.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtgkbdapps.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtqaopuser.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gttrayyyau.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtwnrloaic.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtawrusokd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtlhotsnhc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtkdceolqn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtehoevhui.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtyzekqdfm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gthaafqxxq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtldjpvrbw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtfdupleoi.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtattatwbl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtzoyvxgsr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtptqvtzqz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtoegfmoan.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnqrusse.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtfzgoxpaz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtgfhrrkkk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtlcsssvjm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemjybvgv.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtwcvaoegf.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtaivqelje.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtwdthhdpk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtntgehsca.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtsajkooyg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtlzeluxdp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtmntcmlmq.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtahwhtzit.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtqmmidefv.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtlfkuxfql.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtpzenrhwf.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtfbkeraxk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtrtfxiuzz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtpckvwnbt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtwhxfetmc.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtqmmnkqxh.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gtjzgnuera.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gthllcgfwm.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gtxhavkghe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtivujrqyb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtmqrdizbi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtpraaqisr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjjjzjbl.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtqyseqort.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gttozcrsxh.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gtupugsiuh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtnvfnkrue.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtzgdhitod.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtzztlrfsb.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtqliqeowk.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrzsgiel.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtkkgiuqkp.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtdjolhwrn.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmaimmqnx.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtpjadcmgt.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtopcmhxou.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtrdqxniwb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtltuhhzsx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gteoyejgjf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtfaffhawg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtnhzcsvup.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtfmchyakz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvysnscer.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtnbomvxyc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtioyfdmnq.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gtgezvawei.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxhsafqq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtrdgcvecm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzytwink.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtnjjtwnax.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gthynimfhm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtajwwppnu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtkhcvruek.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtspqdvvuc.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtenltzkan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtguzjhqif.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtdcxzfufu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtjjhkcxvx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtgonklsrd.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtlbsuwxft.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtjdrxkuiz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtqcdqzvpb.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtbfovlijg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtwvhnldyc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtwktrtygh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtbissyhil.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtgtibndce.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtvkdjjqhv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtehfsegjw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gtjxjcyzuf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtqwhaiaou.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtudvdrcxw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfpszlfpe.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtspqkbuxc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtreoquvlk.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gttqaynkra.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtkyluhdte.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtevmyeqxy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gtdachntvt.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtqalidmyb.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtoafmbrvz.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtqhzohqzg.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtzxcojzve.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtdddnoggl.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gthkhgxzyv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtmwhjwpsu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gttcyxlosk.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtczapxfcm.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtuwkhrahk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtjrhnolnx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtteartddx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gteydlxznd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtvixyyjuz.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtxceuhsed.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtjvybcqlm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtorgwzwll.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtaojxuqzh.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtmxgkafgk.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtkchpvigo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtmwsvcbnn.html


<!-- 参考信息 -->