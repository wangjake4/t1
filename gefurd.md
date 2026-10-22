代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acdaumob.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2nktpifwq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2syjzqljv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2dinblvzl.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gt2vbinhbzn.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2sifqkyqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2tmjggnfd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hyxveffp.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2rrvdldtx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utnxcmvv.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gt2tkacleke.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gt2flaucijf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2liivakng.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2grautmqv.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2jnfusyvv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2edrrkjng.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2jmndjbam.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2ayojknct.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2filmwljf.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2bwqnping.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2cotbrjfq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2trnnxdbt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2gvzdzfto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcrxtkas.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2wjafhxxh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2rolmzftb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2wrjbwkwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2ayuzafkg.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2lhupgcsq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gt2uhutbpiw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gt2vdinzlkr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2xkusqibb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2aljtsxyn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2kdywkcln.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2kzradqta.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gt2zinsiycd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibfyvnfb.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gt2llmdqdkp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2tabfmxrt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2ctuysuap.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2ptsldnlt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2wmlqxgqo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2ewknjixd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gt2zrojowqa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2thfsmyyk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gt2oicpcczk.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gt2scwlmaxp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2pabnbhlt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgoslyhw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2lohqljoa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2mwdhkpns.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nneeqkgc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gt2izrfllwg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gt2dowfvowv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2ovyktiuv.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2hzymhwjl.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2rlkirokw.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gt2waldnnvs.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2cxbgjqro.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2qouskove.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2louiilvy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gt2ndscmlhe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gt2bnajytvu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2fpfhybay.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gt2eplpnbyh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gt2yzovnqzr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2ixlvfyde.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2hvmmafcz.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2ebxazlck.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gt2zqlcweup.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2sjbvdgfh.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2jblshyfk.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2xtodmgey.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2swywayio.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gt2srkjztev.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2szjmaipn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2zciqmtcf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2dqnhknpq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2qtscuqyz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrcurbxx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2sffwysbo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2lpoyatuj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2buhtxygm.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gt2cdwukhro.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2kbrixywu.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2olkrniup.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gt2byqldysk.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gt2xwrirbrf.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2ptwlflrk.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2qextggqp.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2glqrdbec.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2ulqwiccd.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhwlruyv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2qoulndqr.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2rzyggwlt.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbupeeis.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2htleixbe.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2sxqgyutn.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2cemtxlod.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2ubwruryy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2lizwjslw.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nedjcbov.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2pjjwmjbh.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2oluglwcc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2qxlbnhks.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2mnsxlmrv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2karzgnot.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2vmqnrlsy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsjqczlk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2fhzvisgc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2wmctprim.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2rwdrydir.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gt2ifrblciz.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2xnuoamii.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gt2sadscbdr.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2uwrzzlem.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2erpgijee.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gt2fhagzcht.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmglupxt.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2ucdvbqyx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2obaqdhsi.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gt2urwfghbu.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2frtklzqu.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvxdlezw.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jmizgvlh.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2gtiygxko.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2qnhowsgg.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2rghueqtn.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2joxskcwl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gt2afvfbezl.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gt2hcoachgt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yirwcqgv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2ekicntvz.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2stjqdtvd.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddhoowbc.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfxovfxa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gt2porcywwj.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2xybfwzhh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2xxmeihhs.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2tjbclfce.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpevbzil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2kelfrwek.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2ipnsxbrn.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2unxskqhu.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gt2equpxtwh.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2ykobreqg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2tmnguqqt.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2gfriuboy.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2gjobjwhi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gt2akqnvwrt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2qzkrrhyt.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2isrtksvl.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2uiynaxwf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2cuipztkj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gt2yqdsekhs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2roexddtf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gt2muajkvnm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fnhheddj.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2dmpnwgjv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xpglpsog.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2akqnrgtz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2zkrwucjz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2ogfiotoc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2gqhnbigt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2aorsoeof.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kowsrfpe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2sjfdzixf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcnjwbvo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bwtgwkpn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2iocuecfd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2uuovxeje.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmvfjota.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubfvpjxc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2cbaofmya.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gt2skopapry.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2abrerbdp.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2lzwlzgow.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2padcpbzk.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2bkfqeqer.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2semvcbef.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2ceocqfmx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2nxaapqwv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2esfrqezf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yupzpaam.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2kmaqgzkv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gt2ozivqsfl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gt2mqjuhxia.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2mrynzoit.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2zkchvqvs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2duaweumj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2dfwncpat.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2unbbxwkd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2bnwjjjvi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2dqjmbkwz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2guhwbxzh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aviuqerw.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2dqiglzxv.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2yaonlklz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gt2mmvzysbm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2cnimyuyu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2pgubrxqw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gt2ivippifh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gt2vkbkgkgc.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2napszqys.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hjzlvkkm.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2urpsjpdk.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wexrrnxv.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2htrhaofp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2roolcvgh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpdsnibf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2qleotmxk.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gt2wnvizkfz.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2alycntdo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2zzypwsqh.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gt2psklhvsc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbqfvgvb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2zphrdvme.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2qayscewr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2fqatemam.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewnmefhe.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2nxukxgax.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gt2bmxddvon.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gt2btljmvgn.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gt2uoffgzva.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2bvlejidx.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2zakdhaad.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2ikgjmvxo.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2pbnuihjr.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2eivhxagm.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2nckblkew.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gt2pkxwmdmw.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2amjzzeak.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gt2bucpchmc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gt2nfpqnksc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2zntnopan.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2slhkazgq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2ztdwdpzi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2jvxskydr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gt2ttzruyjm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2zkgumibe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2ysbbvusf.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gt2sigijxur.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gt2mzacklxa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gt2tofamkuo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gt2izudwoos.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2cgbbnevc.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gt2zkfkkfxm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gt2bdpxerhv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2powbmqcd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gt2lyjsdsms.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2eufuvfqv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gt2jjndqzri.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2fohxepgj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2kgrnjwuv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gt2tcorvofv.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2fphgjywn.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2yydhrxyq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gt2bqjejvnq.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2saglglqb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aexpfkex.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gt2qauuofky.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyoypukn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2tsbpeqhz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2lnakhqwz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2rtbequin.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2gsewibcb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2dveeuqpr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2jogdashr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vqdetdfj.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2pdcpoome.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjwiprdf.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gt2wikggvil.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gt2ffaghbkf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gt2dhioqkyw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2mpswhtxw.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2anedffrq.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwfgotvu.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gt2xgtonnbb.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gt2gvizyhke.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfvmeozi.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmediyal.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrevvbhk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thatlxfw.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2ykjnkgbq.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2ufxlwvli.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2psuasvma.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2qkrbknqt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gt2vjmwfhpc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gt2gezyiouk.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gt2jophmiqq.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gt2domdncop.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gt2qkibeutf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifwvhqdh.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzvjjxfk.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dhmakrpb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gt2iqfsbhub.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gt2clxfbgkh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jilcarea.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aernzdmq.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gt2ntfsymcs.html


<!-- 参考信息 -->