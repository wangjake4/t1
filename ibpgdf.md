代发 wailian999

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2kanxupxx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jxqpzpvz.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2zsozctpw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gt2myilbxwn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2npyazmby.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2tqtqhope.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2qikftiso.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2hlmyqsuh.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2vgwszsti.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsgdkyo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cciaujvr.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcqtvjtp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2ppdacduu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2vozomakt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2ivioppug.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2hdlvqhzu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2vkgkmqyq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gt2bzkoutlu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gt2njbgesib.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2nnlbyoyq.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2bgeipgft.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gt2revsjflf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gt2tajxvqep.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjyfpgpd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2ziweahnu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2nhbpzjqp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2eoegrxrg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gt2uyqxmeif.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2ogaybgia.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2rtgfvhwj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2zjbiqzwp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gt2fqwbycln.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2cfuxjgee.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2hckzwwak.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcqejuo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2rccjjhjo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2wkyoemex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2saypflmn.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gt2ybrfvyny.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gt2qyyfmbxz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2ykjitjhp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2dnoffigf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2izlrkwjq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2zjvmirdm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2peeavfzc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2fldmhmfg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2iogivzkn.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2qpqvydpb.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2ogxdfyyt.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gt2uepjphuy.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdpddlry.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2jjxzphxl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2imlvavpo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gt2obypmlay.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2xgcpcykx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2vcrtcfio.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2vdqegvfg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2owifngdf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2hopqepmu.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2aozztlqa.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2kislksbb.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oloswrgx.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2ntrjbemo.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2wjulwnpm.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2vqgrjlwh.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2lrvtktud.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2dmxyspzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2xnttbmmd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2aygkjhzb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2ifvkcxfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2unybqhbt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gt2mmyvfaio.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2bhqgatwl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2aaaouhjg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xjandfuv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gt2uxdugenz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gybscrao.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2vgpngcbl.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2fxlyczjf.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gt2zaunfsek.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2hdngxfzn.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldejhobb.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2ihqokxix.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2rrqvrgwm.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gt2spudelch.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2fotripzk.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2qgeobdaq.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gt2kbfsgolq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2cgwtosrs.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqskvxpb.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2qtgdphsl.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2zzqaossi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2catelnyd.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlkmvycv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmogtbny.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2larkgmyk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2pghtyqmr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gt2lcwcatih.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2upycuhjm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2vpmnfcyd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gt2efrqsiwt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2bjvsdkmy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gt2xekwcads.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2qeytdecy.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2mqtfpcim.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gt2qpelqvyd.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2hplejitm.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2hbpmlldr.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2tnkpynps.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2rngvedlc.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2bsnzrpvj.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2blbledtn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2qvejmswb.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2wxusqkma.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2kjbelvix.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2qltbxsnq.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2kifdufzt.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2wfsjrgjg.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2innltiut.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2akcpetyd.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gt2lnffcnkx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gt2nmbyajdq.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2gvlrmuiq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2shoygpur.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjswwbqf.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2wppkogip.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwcijsh.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2mnnxphim.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2iuabpkix.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2pemogvit.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gt2thokyxki.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2ipvzjhju.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2nltmhbiz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2noqzzcrt.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2zbknxpdk.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2eoxtmauv.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gt2dnolllrr.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2lgeshtff.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snispyfb.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvfnzcdy.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gt2izaslnig.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2ofvozlar.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2jcqgozel.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2ohqelfje.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryctpebw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2ysrrffna.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gt2cdkfrigl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2gbcixjnu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gt2nyobgswe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ohillbio.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2hwkuioij.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2edxzqzdb.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gt2hxwdlnag.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2fztbiyvx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2ddmeeaij.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2vmuptwuq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqvruknd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqieexmp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2xrgkloud.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gt2koeulhst.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2iirepeho.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kukfrpas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2xzzefsjz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2psryyesz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpfdejoq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cycbccqa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gt2byxiiozy.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2pffreopu.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2tydtvbol.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gt2rvfwplcg.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqspfokc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2amzhtdyb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gt2gtvothyn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2dfprkfat.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2ekzkqcvp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gt2fvfstnty.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2wynuexdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2huesmvtn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjgiucmh.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gt2vzgsceix.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2ikmdjlxc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2hdkgdkxx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2buadjhuc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2ajlsevnk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2psaeeqwa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcwnoodc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2klrrrrwt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2wkvqppsd.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gt2lktsqppv.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfcrwfdb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2fbtnprjl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2iflsygju.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2fdpdrkbe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gt2kqrsjejl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2jusiqczz.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gt2gdoojjvx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2tjcaadfv.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2vymubllp.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2tcayawco.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2omtuolsp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2wpyfdtal.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruludoan.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2giwpoppb.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gt2kawxwvws.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2kwkwkxyd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2qhxozvzc.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gt2lphatvrj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gt2uxrmmwvu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gt2kmwejvey.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gt2cukcywlr.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2vpmlmzah.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gt2gseldwne.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2feqbnruq.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2ssealfjk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gt2naimpcwk.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2yhnqpngw.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2uxygqbgt.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gt2bszckhva.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2nguxawsd.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2hdwbiysm.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofvfwvik.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bguucpqi.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2oktwbxff.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2uarfhkld.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2bcosmlni.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2bfhhrqmw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2dfoivmip.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2xvdeocrj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsritxxh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gt2jtbdlgrv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gt2smdxdnzq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2ocvrlolp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2drjsblqv.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gt2phtlxljs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gt2cwcixvmv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzjwtued.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2kxiqdzzw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpdznpsr.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2vspodhqd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2nyhifdpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gt2pltrxlno.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2hcxhojee.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gt2yuthnofs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gt2ykdixery.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gt2guwcwvpi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2ciekvqjv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvmpzoxv.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2wimuygwd.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2kywoddjo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gt2ircucrhl.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2ydjgarnm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gt2hkwhvney.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gt2iuowatuf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2jmkmwgfg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2azksqnrd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmrypwew.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2broianzq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gt2iaoypbtf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2fsxxnylj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2dagywtas.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyldrjsb.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gt2lawwcdon.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2towazecv.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqcpfjfe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2igawxtgi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gt2lxavxqxk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2oawrkbct.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2abnharyt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2jovqmbiv.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gt2sawpblor.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2jzkggfeq.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gt2lvpdthho.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gt2kzpasigk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bukvrrdt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2tmjuxzlh.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2syxaqtkm.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2xlgbqnqm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2hcmfxnup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2mitbgqes.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2qprmkzjp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdrgwept.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itmtxsox.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gt2sbybvbtz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gt2paeikxgb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gt2kncpfwvz.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2qwmgpqxc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2kempsqva.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2lvxiviod.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gt2wrwfhkyc.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2wwdszxkq.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gt2cgdkwppp.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfunyeto.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gt2pslxxvnb.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2qruszzhr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2oeibtyaj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yktcdpfm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2wtagdmfw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gt2tcyjgxmo.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gt2zeuflhsl.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gt2tzkrhozb.html


<!-- 参考信息 -->