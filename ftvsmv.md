代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbfetnay.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxamnkro.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gt2btuhztuw.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2leuenpkp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gt2qexicmmv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2bjznhkvc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2xtxuxrbr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytjwqvwp.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gt2yqisazxp.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2dufjtkdk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqdvipsh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qfarnyfo.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gt2vahrfijr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hdrcicxp.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2imlmnegf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gt2qsdbpkuh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khsverdf.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2utdoanwf.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2pgkstvxi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2rcfwywfx.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2rwlsypnw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2oqrkfgvl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2dbohpeia.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2pynyrpyu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2infqneka.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2ucfxilmn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2neykohbe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2kohokfwa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2uleaomsa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gt2ybfqzjcw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gt2oawlubtk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2aiscqvfn.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2afhsuthx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2kfnvuxhx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2hjnhyasx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2hzsxzchn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2fcfjveun.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gt2cxdjmkrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2actdrtjp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2nvgenvlu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2zqgllfyx.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2ioovhgbp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfofumbd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gt2uejggnxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2vlmsemss.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2admihplf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2aabmwoml.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2pkbiljmt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2kpxzpywu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2bzbqkjnj.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gt2moknmqtt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2izibuwsj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2hiixryln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2judervec.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2txwhpbkr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gt2dyylcruv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gt2bqbywlyp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqtkaqj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ygqldujt.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2vdkdutsw.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2cotohqiw.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2vetcibst.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2yxglinob.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2dvqxsiuo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcuiosex.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gt2grtbvymn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2mtueqwvl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2vzefncdh.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2yzrcgfoq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2wvhyhvkc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2kyejuafw.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2ooahvkjr.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2itecoyuy.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2hvwcxcft.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2igxhjuev.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gt2hvznumap.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2yogtzraz.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2maqewqgf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2rareanhm.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esrmtjnv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2zghvpbkg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2rqmwwtoc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gt2xhvmmrfs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2nxgvtyup.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2iyijmzof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2ntxspwss.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zhjlrrxc.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2owhgybwf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dcgbvlit.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2tpjauldo.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2ebwokiyk.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcuqmfrc.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2eerrbgtn.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2liulidwk.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2glysytse.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2ctbmrltc.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epqpvmxe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2duhcegie.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2ultnhgie.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyvzppjv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2hzytvtbp.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2iutjbtvg.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2vzlacstq.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksctnmwe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2xfqmbifg.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlzbvkse.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2wjdwlylg.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2hmkoehcd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2lykobhen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2qtovcdho.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnkyfjti.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2fwjgwvbe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mozuypnf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gt2pmhpdqbv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gt2whuwtgvn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2rjqlqsai.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2fqjflkuo.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gt2mnbaecyq.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gt2pvsbzpkj.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2rwuudeyv.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2joodhjhm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfxnczyg.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gt2hnajkoqm.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gt2eaiuhrmv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2ryhjveag.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2tzgpppur.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ztidiptj.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2qfwlearz.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2uzkeoxcp.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2efrehruh.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2nvrqvuyo.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fohvjmor.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2jakopsdc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpvscsta.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gt2auvdtyko.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thtgxngs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzddlaqi.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2fzqjbqnn.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2nfzyxoob.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gt2jbyajmwv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gt2rozxntse.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gt2bpamziao.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2hhuavarc.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gt2bhoroytn.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2phirzrtq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2mftfziby.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2hzsixxzu.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2elsizkit.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpatlzkp.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2wkarwyun.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2tldcsznc.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2cjwnfaid.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gt2rrpolpqf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gt2aqqubhyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2pbuqqwit.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhecaglt.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2gglasaux.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2rmgnazrw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2eyeelznq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gt2xqtvcyko.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2eayfaiel.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ezwiqbub.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arivujtf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vsiuuooe.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gt2unojsski.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2bpffuoic.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2kblvhfdl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2crhpngto.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2ilbkyned.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2hlqvholq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2uosbzfdd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gt2bqzapqsh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2hesdhgpx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gt2dnnnghjf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2kwkvodpb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gt2gfznejrk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqxikidc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2bcdecmcg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gt2smowmhxk.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2vkqencmf.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iltrifzm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gt2qfgrsvqf.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2uifjwqay.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gt2glbolibq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gt2imibpjgh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2cbjrnomo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2uyemzvjr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2gojpubln.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2rnahkizd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gt2hljeurta.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvwszddw.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gt2iphjajzw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2kwcifxmg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2kqxifbpm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2cgkfcais.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atigatvz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgarkalm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2albrztqp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahixavpm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2nydwhbds.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gt2uinfujgr.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2temwcgib.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gt2sblogdwn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ihnojxpz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2lzmipmvo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gt2zucjagqe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gt2jsqjrgsh.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmutnghn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gt2tikorfnf.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gt2ltzhzpjk.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2sppigxgg.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2lzthwbdr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2wckqseqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2kzxfwdeu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gt2osmahxhu.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gt2cmufhcvf.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gt2qyfqbjue.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2swfppvxo.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gt2bavccgep.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gt2slzltdrm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gt2jkzwnlia.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2zirmtolm.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gt2kmrmjewt.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2bumqqfhu.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2vivliuaw.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2ipnboxtj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2xjkdzwfh.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2vwgxvehj.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2swhwgjyw.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2grroeivq.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2wywxthww.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpirlkcy.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2hxdxlite.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2zkoejbyh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2lviebiyd.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2jwgehhau.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2flrviprw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2npsmyrlh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2lwnrzarl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2jdzvqnew.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gt2ulsywzxq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arqityib.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwdfqqxh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2ffmxovot.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gt2ihqfvtdd.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gt2lmanvjka.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gt2clhcfthb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gt2nmnefiaq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gt2ymrdpdht.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gt2nymyejvh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2veuazhzs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gt2bkmqkjfw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gt2kadqbevq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gt2jnqfovit.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2chakgegd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gt2fxopeshx.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2pyemsxcp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2zlrqwxek.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gt2cqddtbac.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2vdonxkyx.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2wbmvkvgv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2cuxocsdp.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2cazatdqo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gt2hndfcuvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2qhobcprm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2vpoonszf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2luzgihla.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2vafocokg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2wjmoezpm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gt2dqpjofsr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2rxdjyhoa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2kzbfgoiz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jznaxnhh.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gt2wbjiitil.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ulmnpkxg.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gt2bltsfcwb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gt2qtdnkweu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gt2gbgttlel.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2ngdylqot.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2tigasrck.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gt2iymrnebf.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gt2obaflxua.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gt2teqoyfmb.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gt2hwtxpxow.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2rvupmvzk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gt2kdkxrvai.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gt2gzrwicxj.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2adhuptrk.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2ubzrhxhg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2ltayenqs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2heipqtjx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gt2nplktfve.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elmxfzgh.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gt2vmtfrqqr.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gt2dprqtvjo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2xgxgpcsz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2yosviuro.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2cegtpeok.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ppuicztc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2jtqxbhzo.html


<!-- 参考信息 -->