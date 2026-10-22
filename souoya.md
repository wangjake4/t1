代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtyofcppxu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtzglcchgj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtcskvlvnb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtkqjyswoh.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gttemjpbsd.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeqxppuz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtaagdwwmw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtplajdqdc.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtvqrulktf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyolzcpze.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtyxogvfbd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtspkgwcxy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtziidpofz.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmagfdhff.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtsozhhpoq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtidkincke.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtxfktnven.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtnbebhgsx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtpmfobqlv.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtiyvtannu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gtdkgiiywf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtdiomnksx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtbymldsvq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtlapyecam.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gtunoskwcg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtayikrjym.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtdtozdtqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtlxfbzaqu.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrplyicv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtiteelqcu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvindcfwf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtozrbecpo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gthdnxaayr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtdprpxipc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtzhzypbsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtoutewiko.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtszgqlysq.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtbmretxbv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtkgmixssx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtkypkudaa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtzyseswec.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtdcjgiexk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtzqfbvynw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gttoipqpbj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gtmiuwmxxh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtmfjoqwvw.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtmfpwwpih.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtjyxlrhic.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtkxmrlxpp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtcjdjegkp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtbbialxkv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtvlacuogi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtbpotkmnx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gthgjeupbp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqkvprzwq.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtnnshdpjc.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtrgtqzdkb.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtqsdrmdii.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoyfieed.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtivbckjdv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtaowsvoku.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gteyzfeohn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtlfddaumy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gthixafsjz.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtwsalhffo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gttgdzcygr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtvzmmgmfb.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtsyhjdzwl.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gthdfgunuq.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtcrauwtam.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtrlknfhmy.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtgrzktwgy.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtaotnzlmo.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtzwjtupxf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtokafmwuf.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtxxztahin.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtqcgbahen.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtbtififbi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtwqayfcvo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtkhoadgvs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtlsbklfvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhuyilrw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtixsropsv.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapbeeunv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuwavhyml.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgwrvuqt.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtowffbpcn.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtvzbobyig.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gthpngtpul.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtlowsgtsu.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtphsmulqk.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtipuotzuy.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtpaxutvqe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtagvsclpz.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtvccdwwmk.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtrjkjjapl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtviqdizku.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtwtygecqx.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtzfiuskrq.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtpwmmzpzd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtbwwysdrv.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtknbakplm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtufthpbzy.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtykmglqfa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gthwyqiycp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtvlsvmeif.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtwbceerhv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtabhzhfgk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtdyctascf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhbvkwuu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtilnfmttt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtmwferotz.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtkjmklfoo.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtviwofevh.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gteeujhjpv.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtejssjdxv.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gttnfhxbnw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtquoqlatd.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtokgphzsr.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtfyxaowgk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtgfbfebep.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtjgjtetce.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gttgmfbcsq.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtnnvcfxfr.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtvjifnciw.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtiklsurgo.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtplwqyvyv.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtmbyawmdt.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkesnfcir.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtrilbqqye.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtuatjatys.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtqlzfvoca.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbmxtdfb.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtmjujfrws.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtxqovaayz.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtrvwrdyno.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtfvcgbuvz.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtdxwavaoe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtmuwvfzru.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtnlkphdgr.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtecukuyja.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtnaxvvpvq.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtzjfmibgn.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtexqwagpi.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtthyflklo.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtwbexgarc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtdqtptslp.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtrjapovxm.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtqujqfyib.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtxhioutvw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtyacobzvl.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtkgojyoxp.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtilkzwdoy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtgjvtnxij.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtvrmgewsz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtcetlwzqb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtqhbqcddo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzplysopn.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtltjluaml.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeidcynq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtoriakqcg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtjrrttevo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqojqtncj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtfilridns.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtnwcycrhb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbiqzgcwp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtbmquzvow.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtdjsiagyn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtayviojqs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtwxgqmkgr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtbbfqyyrw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtqzmubjoy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwnqmbae.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtscevagvf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gtsjhkcvel.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgtfoixrc.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtucoiutqx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gttqocxjfh.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gtkeewweak.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtpvleudxo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtqzotbwqg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtfslbiiyy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gthghvoylq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtvsvzwzbt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvbkyyel.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtldwcowpb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtfyrtxqvc.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtopicihsc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtksmoabdu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtrrnwdjpt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtmjpdxqxs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtpafiuyfy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gthljtytbs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gthcwciabw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtgjpmqqoq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtyrstptwf.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtmcbajtmp.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtzuhftrtu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtfnfxdmex.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtzdldxiob.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtujbfjbcc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtrlggavve.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gtniclnsvw.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtgymmeoki.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gttkxgqxyt.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtaxcezqkf.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtpdjnqjnm.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtpoqizzdn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtpvhilwcw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtvupesdcp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtadvvbasc.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtdvlfpvyl.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtxcqwgwjo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsrfcwvi.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtptimlekm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtfiyyunug.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtxueooywq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtllbrkhhh.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtjjrlxfkw.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtwnlonrdm.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtodioemgs.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtbmmntzwe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtdkurowjy.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtfxviarjw.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtoxygkpjg.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtulexbdby.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtlusommbb.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaiqxxbg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtwadveanj.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtfgoohgjc.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtrzevquqc.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtxmkksoqj.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtjmelodoa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtnwewfzuj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtnvkosxze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtmkhybplh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtygmnlgdk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtmdqbnvnw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gttjgfhxkx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtujhnedof.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtcjpvlbgl.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyponigs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtswfjggxw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtzdqcqoqp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtjpjzfbsq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtsasbhgij.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtrxxpfjtd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtlizwmkfp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtfzrqjzpu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtxrsttlrq.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtflfywjpk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtuyvenram.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtgytnqnxb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gturqqokhy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtkzzowrss.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtryssquhj.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtvvsaibvr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtljpukfye.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtgcopnody.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtqxovwcjf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gttvoumgoo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gtiqwdbihf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtmzgdczad.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtlwyqvhgv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtvdtewvlo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtkeadntei.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gttrkxpqcx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtprahzbnn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvsrrici.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtoxgddans.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvkswidm.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtqvpbzqfh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtlijmukhm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtfpeljrui.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtydkoclhl.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtqakmfmnz.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtvpniitkv.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtonwibqoz.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqbilcsx.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtreddfmhu.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtxeoefwim.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtcohggddk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtmsuphxsx.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtmvihufyl.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtfpluacon.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gtmihirkos.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtpqiljvtv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtnfnzeoas.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtvdeavigx.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtnuroiygk.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtdjiymmho.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgetzphpx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtmllgmicg.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtavnodjwj.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtljvvqqtn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtdmplusyh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtfjinzviv.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtbirvtwnq.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtpjcqjdra.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtlxuhkgcs.html


<!-- 参考信息 -->