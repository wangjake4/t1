代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gt2lnliqiog.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2ybucqijo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2sunamubi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2ugbrphfz.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2lzfhwjvs.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2qbdqzvsy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2ulwjxlfm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2koqhsqsb.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gt2vkrbysif.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xhxbjgcz.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2buqpppbn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gt2wkmpvzrn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gt2smkmcphm.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2tcxagooj.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2bqtodsqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gt2qgezzaln.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2hmiafmsk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gt2czkfdkmv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gt2cigvapca.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2mezlztau.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2jxixgziu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2oscfupro.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2diyarlni.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpsaasnu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2lheujwqi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gt2kzrxcbbf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2ogfstgps.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gt2fkeevhoh.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gt2uyqppnrb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gt2kuujbpgl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gt2wptiwchg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2icwgztxi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2ijydexxp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2boqxjlfw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2sbmevgmo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujgtqixp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahertbhq.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gt2rlkyeycb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aitamekn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gt2zmfrnnop.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2czvcanjj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2rkxpzzhs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2wauvygjt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gt2xbejeoqe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2xllzwnng.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpwwdwvc.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gt2nnaediyj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gt2fvubdrmt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2gcvhymwy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2shcvpqvl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2vykokuwm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdbwhrfz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gt2fhkjypev.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2wpafmzob.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2rwhxnjhb.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2templpqr.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gt2quhkebub.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2mkclnaxx.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2dsuenjrd.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2foshvhkq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2pyjoenbs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2jaxdlekr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2smopqaru.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2lsmzebgn.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2uqyealsj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gt2qdbrmeov.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2elzskhrl.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2irhmbiio.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2cnirfwmm.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2dwgbsobm.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2lhzkgbqy.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxhiobed.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2dhwrgijo.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilpemrnt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2zwxvrqqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gt2fznoeknw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2vravlfti.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhdpapja.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gt2mzuoktfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gt2rdjscgma.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2obnzywkb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2dfxkkhxj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bbopppwe.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gt2myejfkwr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyhyhpao.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2ppphqojj.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2sqczlimv.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gt2qnjjngdd.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2scyzitgy.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2jhafqznz.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2dbaspbkk.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2fgfemdbi.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2nodhtkpc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2hbbngwgi.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2sulxepnu.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2rvyhakjx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2davyedab.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2uyblsmxu.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2uhvgtkpu.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2vuhbzavq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2udkvsbzp.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gt2ojuwrcdg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2eqpwwmsn.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2vdnygcfo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2rxyenapp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdjjkleq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ihvyswik.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2jarxetsx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2pjpwqnyl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2kbailkoy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtourpnl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozamgbsx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyhejoc.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2lxrdthwm.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2lkufiktd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjqwsyf.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2lxznmhez.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2mlcqikxg.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2tztlnkob.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2bsuurhdl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2rddhcbxm.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2zjttzezt.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2kifilopb.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2glgazggq.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2xmotvrps.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2ixdzrokq.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlofrpux.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hklbdhne.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gt2mtxysdza.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gt2qbvzajhc.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2ucxbsxrm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2fcgntbra.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2arwxkstn.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cczfxgdy.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2hckgaddr.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gt2nhaypjvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2motxqnnj.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2awbhxxov.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikcnmcde.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gt2chfprwdo.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2gncjxidr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gt2bfqydgno.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2cmzhymze.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2aqfnmdje.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2zjymcwxx.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gt2mehczrxc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnubpvho.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gt2frsssqkb.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2kvevppgx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qatqanyd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhvuueu.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2akdoqtpi.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gt2wvrxyumy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2uwgekwir.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2nsfpuldk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2sohsbjju.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2bjjmzxtp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qqxiyduo.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gt2eycyaqdm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2dwxbdhgd.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2jfgwxlep.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2lkovegsd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2tfwjpblx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2duazzmmc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2vipadsdp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2eyfwwpjl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2lvoziatm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2amnwdhey.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2zefooour.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2lmfepiio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2shomedsl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvzhsups.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2pwlmilps.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2psecokje.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gt2bwdtgcpa.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2uyhykydu.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2avmfwsaj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2hffhfvbk.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmmdobji.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2ptzivxrc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxejagdf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2xzpwsfgq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2czchtfut.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gt2rfzpnpma.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2xkkcnexm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gt2lyrqdjdy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2esazyzqx.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkeoabrw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2oyqybrau.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2mlnzmbyq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2sbcnvqhx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2qbsewkpn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjyjxtay.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2fcxwqegf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2jzkskgpq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzluftwm.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gt2bsnlkyxg.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2xtqjsenk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cqrhaqly.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2ghzoyudq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2gneoameg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gt2dktiysdg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gt2yppplbaz.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2lduksreq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2uzmnxqvc.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gt2ujtzdcat.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2fufhbenl.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2aktwliek.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwsxculy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuffovor.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2woikmoad.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfuozwv.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2sipopsse.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2hqgbddgn.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gt2jfetssma.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2ftciojap.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2upwxvytv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gt2kazzukio.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2upytikcc.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2ypyqmnfa.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gt2afutudmn.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2rcrzbrvk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2smoypjhf.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gt2hzkxczth.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2axnnwufw.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2uqbkgfpt.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2qwdggwig.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2rozxxmbg.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2lxedxabh.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2pappuuhb.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2juwiyaml.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2pneyjklr.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2xawiykai.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2jgyigwil.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gt2tvdwxekd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2plalauaz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2fztxpvzx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2illemhvf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gt2bofhjarg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2ahioxshj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2begbagjn.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gt2zgmwtmid.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyuetdyq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfphnxtf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gt2krufxnia.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gt2ycrjikve.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gt2oexuefmu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gt2jxnjsmei.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gt2sxbjynem.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gt2nyibmmct.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrjykxyo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2xjnorrpu.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioqvsbaa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfmrcnlt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2mqlrsiwa.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2osfoybgv.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkyxbzub.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gt2qtojaoes.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2yqislefg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gt2iomvmibw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pasqosix.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdmrzxwo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2vrafzrff.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2lwjlvpzs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2wfsbnkbk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gt2ivpihbrv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2ueaxphud.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2uimyxjoz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2anxvhisj.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygpowrff.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2oxcnguvs.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gt2cnnxuxct.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2snagsceq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvxmhhff.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2hznpbfkx.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2gkqhyhse.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gt2fltyrknh.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gt2uppiziqm.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gt2qfadnjwt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeysvaf.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2thgxfzsa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gt2lceykhcp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyethnud.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2holxezci.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbitufpq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gt2ueekdzmw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gt2hincgnel.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gt2ohzgmgpz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2qcopcqhc.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gt2otgzhhgi.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gt2swrnuxkh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gt2colwumys.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gt2lsuifwqk.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2bmfwuibo.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2sejmvjrc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gt2eoanocul.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2ubexfjjd.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2oyvqjrdj.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gt2drkhvjko.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2safogxyk.html


<!-- 参考信息 -->