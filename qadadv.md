代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2pjnxhdrz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2ltekyliu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2grzcxxbe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2hycezqun.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gt2lvnfills.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2yzohriyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2uqfohzjs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtpiinjs.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmzugfds.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2miolcirz.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2cxunjlhd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gt2npqgqiyw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gt2lqsxtfcx.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buzisdxi.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2euvczuuk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2sqdpoijy.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2keoihjmb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gt2ptpjfcsw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2ixgxrcaj.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2qqxqeoof.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2npesfane.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2xdsajnzi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2pdrnqvkf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2hipmkdsc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2glftyhfl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gt2pifcigqa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gt2ekkapmpr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2vabpnhru.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2rfrabgqb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gt2ejqrbtdf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gt2ncanmzpe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqbqqkep.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsgtqjsj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2pvmtfbru.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2erjjxrhc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gt2yxovhoqq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2plzdsvkl.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gt2jftbzhkr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2rojcgili.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2errigtne.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2kdlnyofv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2exbrsauy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2uwixbleb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2hdbgonck.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gt2tnbickbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gt2vnmvkhqr.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2vnmsrvgd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gt2ydfscmsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gt2locikjld.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2cqnaanbu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2agwkadnu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2yifbjmod.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2vqpgnhns.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gt2wuocdrvl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2umlwdrva.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2wvqbyjzr.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2tjwtzkxu.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2ihrwcicb.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2jaaynisl.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2kuwwvuwk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndskkzmu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2uwbpeaqb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2kztvztre.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2novnyrxr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbqovcui.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2bxhcryvn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2kksnrtam.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2vfsbhvdh.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2gpchdipv.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdqhxngy.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2rydqtvqa.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwubmjee.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2ejbiutfo.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2dzrnctqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2qykdplgh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gt2skbvhqhy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2hstlkpup.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2nrdihrod.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gt2btneiicb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gt2xbxutfnb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gt2iubtiqbn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2usywnrsd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wadzwbot.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gt2atwmvsap.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkumjohv.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2xugcnvxz.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2gtfglyfp.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2jsvhhjyy.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2njzdosrg.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2pnotwuaw.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2rmxdrxwm.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdrakarv.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2meqgigqj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2cyidioms.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2vsupokxr.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2oijhlour.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2oykryafi.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agmfvrtc.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2akdguffm.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2hhxdidlz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2fxriqpny.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2nybrxoyt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2onvzdlho.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gt2wywxkckd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfjzlxts.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gt2tmlkpupz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2kvcunpeg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2zgzmnmvw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2sxeychto.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2yjpwybtr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gt2anwhffoc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2ezgngknv.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2sgoqizij.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2eabzrdaa.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gt2ncmdjsuz.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2plwckmkq.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2nqpskxgh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gt2egxtuqvb.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gt2iesiweqe.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gt2oesbwrqj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2zxgfbntv.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2exbpymil.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2usullsar.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2pubrzcww.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ewartltm.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ngpepkwn.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2ymofnlmf.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2dwakxpod.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2tludfgtw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2httvmhle.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2aaufwvik.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2ijuzyhrt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gt2nqenqrsw.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2jtayfgrf.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2nvihmdeu.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2vsynopen.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2rwvinofg.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2xlcetxwp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ifqaqspa.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2lldjjalo.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2nigoqpgv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gt2rhrxhapk.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2ylyxipwy.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2apzxmspk.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gt2cyhqfxxp.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2hhaqdtmo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2xacsmcup.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2amwlpmgs.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2yidetswa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gt2tmvnqgqo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2bhetmzny.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2cafxfzgp.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2hdhndsqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2mfyatamp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gt2mmhlyrqr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voufhyze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2wcfpaqku.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ydanvmjx.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2yivvgfoq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vjxzmkmj.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gt2zslnefmw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsflbnpg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gt2piokdeea.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2tpjtrmve.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzeulgnj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2qwegqwrn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmcsacju.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2tuzrlnmw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbfdwqr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2ydossjpe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvyrgzon.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2myesrhcd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2fjnwsfof.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2edayviqb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gt2wjcsvkgl.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2flmfwawq.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2trrwsjsu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gt2wfmwgowa.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2pozgbtef.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gt2tybnhjrz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gt2pkcuohnm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2avhgafat.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2hnzmkstb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gt2ozizzyat.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gt2ffejgucv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2ctubnade.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icltjkmn.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gt2hpjnlwgx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2hiqeszva.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2hjnraivs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2vqpunpjj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2mhzvpwat.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gt2tmrkisro.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2pjqwxpyz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lrkjmeuj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2zmdlszey.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gt2erahrlbg.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2baoxcslv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ggwqxpvh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2jbgtmvnv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glsqfhsm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gt2nezlucei.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fngvnuih.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2moiqrtmo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gt2yichcfdt.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gt2dvnbmlsb.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2zjlzyzmd.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2nktluhlj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfhuncyv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqnczysr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gt2wxdiawaw.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2glhrromf.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2exwvanqj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2fpgmgpde.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gt2ymlfotkc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2guzpelpp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gt2znbaufor.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2gbvykwda.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gt2rbjzwvss.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gt2ekwnahee.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmzzoibs.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdoawlka.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gt2txffmbit.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2kwshnezz.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2otcniknu.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2zpixvbzb.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2jiygxfyt.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2yboujyvx.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2zcxepimr.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2oopcyjed.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gt2fnwtqhtj.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2khvwjjwj.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2zghwsxpu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2owqgyazz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2ysrvctvx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2qrovyrlk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gt2gbjlxmnp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2cozwybvj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gt2fmnmzpyv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2vwbwgzro.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2jinbwqxm.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2iutxczkn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gt2obxfnhhx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2danpzdvm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbnelorz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gt2uirgjlis.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2bfygutfc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gt2wsnxsrsh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gt2crxgofmw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gt2tdnzsxfw.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2lusqoaso.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2kcfldqgu.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2cdtoejos.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2gswtohre.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjswpfgc.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2rckvretq.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2mggxzcvb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gt2brllomlp.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2eyfdansl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gt2boqyzuio.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyhuhlye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gt2avpymntd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2stsihelq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2ilaovzfo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2cktvqdsy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gt2nmlyfarh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2wrqmxamz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gt2dmhsgixu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2matrwzxt.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2xiprmmnc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2celtqrrp.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gt2loudasdu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2pdqrzwvg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2wnhzases.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gt2sqbelozi.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2lcifmvsk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gt2bjniywgh.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gt2ajwmdnls.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2vswpdfiv.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gt2crjgfgxn.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2ipblklqv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttghzwce.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgoxqyxo.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2bzwfvvvp.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2cbcwuktq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gt2glkpcwpq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gt2hhiwmtao.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2gjwedtyg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gt2eaqbaioq.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gt2zmptlffr.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfuguuvd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gt2qeuygzsl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gt2iepzlqhs.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2oeoehitq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2wfbuqtqi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2btrctjhq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gt2xnnbqclw.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2yksshrsv.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2onwfviwt.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2ysrvehyu.html


<!-- 参考信息 -->