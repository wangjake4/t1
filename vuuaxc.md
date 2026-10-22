代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gt2sfhlnwbu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2ytcqgiga.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2xbgbekvw.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2dbkzxpmf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gt2dcbdwffm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2bqwbxthc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2wpbaejeh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2yessepvf.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhsseuwo.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gt2qupojlgo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2xjubuvos.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qnyyggfd.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gt2nxcoalzj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jbbmfnwh.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2lmbasegd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2snakmabe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2hlykxxiz.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2rwxastku.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2vucrsdpe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2prjkpqnt.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2ctkujtch.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2aujyspwn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gt2gfnzsoza.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2bssewtun.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2qhdyttiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yftzlnnp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2nnkawmhw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2riuzbyyn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcttcfkn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2ijtvigtg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gt2hoqbywbo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2xvopejnh.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2puuxxcvg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gt2dwvqenlb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2rpzqckix.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2kogvyfoj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2iiyabpzp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnwtyjkk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2cksqvkwy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2xhqcwirt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gt2npgoijyy.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gt2wjwlwkkp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2anlcprbd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2qrypjbff.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2dptgfvld.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2mketfuxp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2olrlriyk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gt2xnhkfzbi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gt2zhfybpcv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2hgwxqdrp.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gt2mbgmttqk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2kzntobag.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gt2cfwvvdck.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2ayyndjaj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2leiygngm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2kfcehiye.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2hysbbjvh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2ygnlcazx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lptwfoiv.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2ymczyxbz.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2dfpmygge.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2przqtncf.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2kyytpfed.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2mqghtoxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2xtabvoyw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gt2xoeumjaf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gt2krghgcxx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlmgygkm.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2wletwjlu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gt2tfvngyqz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gt2lljbkltf.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucaktyqe.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2dfcoltqu.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2ptkokaah.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2mrpegnwn.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2bnftbzrs.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2ybqofkzn.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gt2chbgpmyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alhzipat.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2dwfwuhyg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2jslrvakd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2oahhwjso.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gt2znyzyypp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzgumlut.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2cikpnswi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gt2sxfwyvbj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2maianrto.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2yraqwior.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tkrjokeg.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2uxhnwpoy.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2sbagbuax.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2dxjpzigi.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2phnoktrz.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2fjtjokgv.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2awphwnqt.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2mvbmxvju.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gt2jywshrkc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2guvrrqra.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2vskfugso.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2nmivqqzx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2fxhiswfy.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2nuiuchpw.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2rzfjslur.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2wzryypvo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2lhmyaeux.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gt2otbtqrdv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2bwztnuqf.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2emwxwava.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2aklogfjm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2plxztbdg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2jxsvwnbt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2vuhmypmj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gt2uaqibfuy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2qvdjyyso.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nshyndvv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gt2encjmtxd.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2psfmkxfg.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2nerpbuli.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2vhvhkhlr.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxyzndtv.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2dzkdmugq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2zogznakg.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gt2wanpnaih.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2cafttyid.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gt2unxihbqy.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2zmtaoyom.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfyrgdzw.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2jqigteiq.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ukdndgoo.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbjngvib.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2aoeuvfoi.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2kymvvgms.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2lhexudrq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gt2xtjeirme.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2czmjsjva.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2lrnltgmq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiqzppee.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2hduwfbmq.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2zccldawj.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2pzhxzenr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnxuqymj.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gt2asefegan.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2vsoynbga.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uitwlhqe.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gt2ssrizcnk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gt2bxvfvtfu.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2flhxweqt.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2xdudblfi.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2ytvpuzqt.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gt2dyuazzdf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfraeatv.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2meoohfcu.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gt2rvcawuno.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2quczjbqx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2xqmqrhqr.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2hnfoackv.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2jxtmwxwz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gt2suogetrb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gt2ykqzmdaa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2ripuuzsy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gt2ahwyxneu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boavyhzb.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2ccduhrth.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mlcwyarg.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2megdiwdq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okwhhbnh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2jdzxyvud.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2peoiwvpn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2zesqovcc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2zythklfx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2maotjjch.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gt2nygjqakm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2lehvpyru.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gt2vtyavddh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxqdriad.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2tvxubrcu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2fwcpqnjh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2ojkpljrw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gt2fslncsin.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2inyrlram.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2covixuuo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gt2cuegipxu.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gt2mhjacslm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2gwlrzjmk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gt2hqybjyfy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2xqrhelkg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2rtoswzya.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2fmyqnlne.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gt2ucqgxvqc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpjjvfu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gt2wtcoqisl.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gt2oszklcgo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2yirqsyot.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaodczks.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2rciouajo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2onsyfoqu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2ergvteow.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2hymvfjwz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2qkpyyyhz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2wxvwaedh.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2rfpnmcss.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2llpecdut.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gt2jtrmvvbr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2czpuptfs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2ibzkeqlq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gt2edbpbvtd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gt2ffwtevbw.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2fxvfzgfp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nziyoxai.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2dpysbfnh.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2zeuwxngm.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2nuarflki.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2fxgifzas.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2vauenoub.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gt2knfsmxat.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gt2zejhueaa.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2awucgznt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2fixihyln.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2uopooslx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gt2uqvdjueh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2irldzkgz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gt2owcvlktu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gt2udnjncri.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2alhfqpys.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2japhvnja.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gt2nliyebst.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gt2dmgztezu.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2frgougrz.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2wqtioacg.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyffqdku.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2rokeugzx.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2cuzxknsv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rplixldx.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2tzephwdv.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gt2keuokzpk.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2liyxyqmm.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2pkpgegyi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2ckwaxage.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqfeglpw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2iunkkqmv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gt2jrhpmiis.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2jjfmryud.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emonpwma.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2cxxlpkwz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2gpgwphkm.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2upjdtxdl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gt2cutbnptn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2eedvgabh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gt2nyhqneap.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gt2xuqscgok.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gt2lghclrjo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2mzglmxka.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2xdljiaku.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bamnhdnt.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2eltoicbq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gljaeddl.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2nrmgeasd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2sqoheavk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2bmeoeuia.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbpzidd.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2fjgmqels.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gt2kexdcoiy.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2ojyyvbwe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2epwtzakv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdabmtvv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gt2pcoomsyw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2ruxlkrka.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2evoyjsbf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2fypcqrvc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2zwporkrw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2qyxmmbim.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2fjlgkhkh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjjqghja.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbzlmddv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nygmrumz.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gt2yovruzmr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gt2ojzwpzym.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gt2xcfohnfc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gt2yevqchzy.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2mpcqnhtr.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajyyjxtf.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2yafafyuj.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gt2inouixfz.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwmyrpbv.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2zitjiazl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrjaozxt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2kjlsdayk.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2goidyilu.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2kdppejpq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gt2jbrvaoyv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gt2znqmhdtv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2wkiutlkv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gt2hmtiboff.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2uwhxddvy.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwziwcgq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gt2gbnqmkge.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2vtvcmdmo.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2mphkumyv.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2isxvirtv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gt2irawjrhl.html


<!-- 参考信息 -->