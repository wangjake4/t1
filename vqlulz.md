代发 wailian999

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2bsplmtwg.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2hvgzujiq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2oogfruse.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2igkzzyfo.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2uxgdybkg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2qpxqyzzz.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2litxxyus.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2ndjogdeg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2gowqiayc.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2xwtswnrg.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2kexwunok.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gt2aduvrdin.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2kzmetcsk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2ogwomkla.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2fnfuiajx.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2qlhwfhqr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2thfbjtbv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2tnqrbrbz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2eoiorxxn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2ohdjmsre.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2tletptgf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gt2qlllzuuq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gt2kygsbtlm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gt2dthfbwra.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwsnlrcv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2orddhwug.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2qynywqlk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2irufbqri.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2hjpurrqb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2vqggevpa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2xxnaphcv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2gsugekgc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2cfiutbwp.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2dzatyldz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppnrkyhp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gt2pumvtfec.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2ysmwyyge.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxdvwphf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqqlosnr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gt2fkryqpak.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gt2qembkgva.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2gygolyag.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gt2bgbacrde.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gt2txvqgggi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2skdildin.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2ivdehzbe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2ludpxsjg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2uskkxflf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2bpprttyw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gt2ufxswoku.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ijroqvco.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2fgujfrto.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2hvlpwjyp.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gt2jijyyxdz.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2gfvlsxis.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2mofbksee.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2enddyfla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2yjourjbo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttpjyjlc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2fxvvjmja.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2btefwxdh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gt2bybahvtf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gt2myafpfie.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2jxecmzku.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2llchqknb.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2ckuklypi.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2oxtkjtmt.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2vjciecig.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2aqnuydxm.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2vebzhyqf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gt2qxlpswnq.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gt2mhmaohvi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2dxcwrxel.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2pbrtgacc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gt2kmbrioxs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2bpavbwwb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2rqtltryh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2xrqldawl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfhshbbu.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gt2nsqemxyr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2suxugeua.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2jzkvcxps.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2gvgzxvdo.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2mdvymfpq.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2utkljcim.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2gdwagpzi.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2ffjextpn.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2byjwnwur.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2gmaxssvz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2grapvkyq.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2kmzztkdr.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gt2oemhszbu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2ikntxjrp.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2qpekvzvw.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2hoedvugb.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpukjhhc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2rflfafeb.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2ryltzxol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwgkfqyk.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2qjrwtusf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuxyowsp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjfhijkd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2arvheehk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkacwwp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2gptpybvz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2oemjxaxf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gt2eaoedqdq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxecuogr.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gt2ejwicbdh.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2ynzsunvw.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2wjhwkudb.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2qhyofwgg.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2nytiewdx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2iaacthqa.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2cmsmhqfa.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2pcqaerwg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gt2dhvlhoid.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2tsjkoaky.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2firvfefx.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2qcawapnv.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvuglnkw.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2pqdsrcce.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2vxyhhgyo.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2kjbhdnju.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gt2hxdrwicb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gt2algpairj.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2obeprqnp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2dxpeqozz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2bkmkdtax.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2smjhjctc.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2nqgdusth.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gt2wdhchqdz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqvikxrf.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gt2nwntbctb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2wbxgcbrs.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2iiuxokti.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2bosaidrs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2japdogzj.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2hnwhzbny.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2xhoqllmr.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwdxfjar.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gt2pmdwolnk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2dejbppvu.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2vsvftanl.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gt2locsjqsk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gt2rnxknzjf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2jgabxvdh.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2vdtskqxr.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2nzsbygjs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gt2anxggvsj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gt2rqucpbwk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2vhcuqsuj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxlgjnfl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2enpzjpcn.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gt2onnquzqd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2nsaaknfi.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gt2polplmzj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2oyubqswn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2sfcjnvzj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2fzckwolw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2kezpxlzg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcvbwxmq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2yprttcti.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gt2gewlzwaj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkiiwroq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2xcpwyygs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2qampgpga.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2lpnwmusz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2vztjitfk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2ytnhhwdx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2togwimgz.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2awiyvnwp.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2ihnjrbwl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgvhkkcq.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2bcstoxzf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gt2nvulsuth.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iipxylzx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2jnzcrujd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2oizvaans.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2cpacpgdz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gt2lqgvjhqy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzfhqznf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gt2wrvjqkpm.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gt2lgibijfo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2cdopkrbm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2riwzohwr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2vorcukaf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goshxshj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2bxuimedv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gt2jdtizfpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2rsgspbaj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2jvihnrbn.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2iztdnjpi.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2iiwbgpdf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvfaegmf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2hrwjvgpe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2hkanqfdd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfgbdyog.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gt2vkrgxbey.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2qccigqze.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsmbdnoo.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gt2bzxvhamg.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2mqlaeupr.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2yfthapvj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2tojmqgua.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2zzzfhkft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gt2zsplkkxc.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2vtaxwbbk.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxyyxspu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2pdjpknlp.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gt2iqwnuwlz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gt2ytseuoix.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2kurpmwhw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klehpzsl.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2dikzanhc.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hongrtnn.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2curjgzkm.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gt2whmkjrvq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgaubbhq.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gt2wgceuvkh.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ryqoqwpo.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gt2hbsxkzpm.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2fnkufrst.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxoanzk.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2mnwoajqp.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2njxitxlh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gt2ucmgqpmw.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2ppvfuvxa.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2zdsqomag.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2ohojnhdn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2bglyqtrx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eztvdqmx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gt2inpmfnub.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gt2fkmtranm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2njfnzzzf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2dzjmjjel.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gt2fhuffjtd.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gt2aekmojql.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2eflwuhkk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nledcrgz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gt2vivyivyx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltoxyfmd.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2babqpdno.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gt2eaxbutsr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gt2wocjvchl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gt2yocndzvg.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2jhjohvpu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzmigdnd.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gt2scvkezla.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2nkqhuafx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2ywvswoqv.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2ynrzhals.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqzfgxuo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvlydmak.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvfcjotu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2ekpsqccm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2oiyycivb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2cescjhus.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iohrosyi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2dhhwmmys.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2rnbutyxt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2fgtervoi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2uymmlxjh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2mduxuyag.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcespceg.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gt2ngwyfvbf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xwffwkls.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gt2jzvaokvp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gt2dgfrutmi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2qytaegqn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gt2auojufys.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2evvpownp.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2dibghycw.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gt2bmpgcpug.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2zqvrkuvg.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gt2ohejfuqi.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gt2ddwgshnl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2kpgjnecd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gt2gyjkperl.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2aovxtqcn.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2psrbidce.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gt2hjypthbm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gt2xarnnsir.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gt2hbdtyyef.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gt2ixcqypkw.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehgryxfc.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjhgfyke.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2pkictxok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2bwceiprj.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2pvqoqrbb.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2pfddcktg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2pewljvxw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcbskcac.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2otrmrsnz.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gt2ivukxtdp.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2yhpxiaop.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gt2zxpnmyrf.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2doyfycmb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2fkcetaxo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nolkxnkx.html


<!-- 参考信息 -->