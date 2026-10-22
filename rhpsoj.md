代发 wailian999

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gt2xgwzsyqp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2isscouap.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2wtfhmxfl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2dpyaafgh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2xwpcwfyp.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ongcahwl.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2qqtkmqrc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdpnsfjc.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gt2fuvgpmyo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gt2kwopjulm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2chdtkjqj.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2wumualui.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2yphnicmw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gt2pskskkoe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2wkmhsdjp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2vqmcqqhb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2taovoadc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gt2xmeteovs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2ykyifrku.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gt2qsaqfpnq.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gt2zwrtpmzx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gt2gtkhucvr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjrwlagm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2vwlrxwtl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2kkllmyae.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gt2jssregyq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2fygpcqjm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gt2kfcibisn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2vjucbyeu.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2lmuhaqfx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gt2hkzrbigd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2pizqpfql.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2irmvyvmv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2wpxkagmc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2kjtyhntu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gt2ohjdagvf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gt2hnpeqlet.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gt2bwhzbybg.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gt2cgiogcrr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2dfvyerfg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gt2cxsvmvit.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2hayhhxrw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2ajskhcxg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2bgkqjmnb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2mcegcimw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gt2eqzqvvqp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2hpmpbpef.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2zekrmqex.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2wmrackcz.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2qqtdyzap.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2bivkmmtq.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2mpyhkhqb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2gmdvffrg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2hynxzrlr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2qdddvqgj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2ckzxsogu.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2mxtkyrps.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2xsmbfmua.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2zzomezvm.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2ieharhhr.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2xupcqbnq.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2nertjsuf.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2ntmohsst.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2keycsfsx.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2vwibzqyz.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gt2ffuusgtd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2pyrqxmvw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddgvnvch.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2uetluwdn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2hyibdqfe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2ovcxtbqa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gt2afhhejgk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2sgkjyzpr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2uglvnsxg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jtujffmk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seiwplbr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gtaokmmz.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2zeuhhthz.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2lblkrmll.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gt2djpassts.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2gawanybk.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2wvjyimjb.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2lypsegon.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2suqhdgsw.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2pljhauei.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2casvcewi.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocwuydkt.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gt2ncyxijtg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2vicjymjg.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azitskoc.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2grbwyryp.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2dztiswbh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejcfvdcu.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gt2kqcpaded.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohgohbwv.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gt2vujoeyph.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gt2zbngbhbq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2expxitir.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2hmzglzpi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2tcmlhpvx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2pnqikvgf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2rrbayhzq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2pntbntho.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2teqwmydy.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gt2ephtedlc.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2qgbglrtk.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2eqlvmgvs.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2nmzvgbqc.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysfvrdzx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gt2otxecgib.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gt2dbjkgnud.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gt2jxoymxdh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gt2cvawuars.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tibmqles.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2hvdnlupq.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gt2ujmnrwdu.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2nbfbbwqc.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2znkdnpok.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2iedwzqek.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2zgbufjwn.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2rjcnmtmz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gt2aotlthtz.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2towpmwsz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gevtygkf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2oujsvmkh.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2qjxssubq.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2suaywkkl.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gt2takcbjmu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gt2ohiqynzd.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lizjxuus.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gt2swdcfsdd.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gt2hlsdepwp.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2nbmjffwi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gt2gwecsenv.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2khuwilmi.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2zxmuyrbf.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2lnvhgoot.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gt2jgsjskmw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gt2szauigdb.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gt2etujtmxd.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gt2ioomsfng.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2ftsymzpk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2zovuijup.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fakoxpcy.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2apczoegi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gt2ztboxprs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gt2cnyqnmvy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2wmepkqod.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2bfvizwzr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2eetretaz.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2zzuyvjni.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2faaghupi.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdlnyqon.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2cagyzrrm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2ywswbnua.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zosmuzxc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2kzoqhdzg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2uwvmupdb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2qoubbkvz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gt2vguwmdhd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gthmxffh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2auanekvh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2lftdmbde.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2grfeimpy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2rxkvdfxs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2ylhmbhui.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gt2yguuepwa.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2kimicota.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2dimtxrcg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2dxfcyqrf.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2cmfhvusz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfcpddtz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gt2hvcgeeqk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2hctdhbui.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2mhoqmapa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2znkjlsww.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2uwixyqjq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2wuvmysiz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gt2tulfveeo.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2kschfyfo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2zruwxxvs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2gpwleaad.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2usmbqxub.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2gbnbtwqa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2mkscaebm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2qnoekfzy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2tdwwrqvd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2slraiowx.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gt2ijblyogh.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2tvwcomub.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2weyyabzq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dnwrtgto.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2oxafmmdv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gt2vuvgqvop.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2ddlbjefa.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gt2wtzhfdxt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2nllxypyd.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2ltekqvpl.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2cgxjmxpq.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdqjreps.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgjgtckr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2ttwlirqo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gt2tgwshdsm.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2vuydyvsq.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbhtibeo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2xhufpkjn.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gt2icdlpliq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gt2saebayfk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gt2louecwgk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gt2rnsnvvpx.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2flkimrmv.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2ymmkgekb.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gt2kfbvwjwv.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gt2hfnxzmtm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxtdxp.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gt2wcfegega.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2pkmmfllx.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2uogqrkkx.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2xcpgqrwl.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2smzhfdeg.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2cbzqedok.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2hisbqpvb.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gt2mkmtgoll.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2rthzpsst.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2zssbsviy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gt2tdgfrgul.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2radcgyfi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2dxqjtqvf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2kqgonvmv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gt2rumxyeef.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gt2effmbpwo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2ybkiamqi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2cnargcxm.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikunnxvh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aswnucfo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnolljid.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gt2mjeqjpgg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gt2hcdfactt.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2xntkbjsg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmtmflzz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2qisoymyi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjboylqp.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2owxxbzqq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gt2ldfdluzy.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kftqqdqf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2fdtrlgxj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2yledrasj.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2nwiafbrb.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2kvgaykqu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2pcfkkbdg.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2osjbriec.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrjtpoia.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2vqfoiprf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2eirqkiaf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gt2oxsevoyo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2nhmodxej.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2mhrnrrsk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gt2stoghbkg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2cukxedxy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2vctnrwdc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2frzvyhnl.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gt2cangdhxy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2umegpton.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2nzaptheh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gt2osovjuip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2mlmgyewu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erangvzb.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2hwibiqfi.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gt2vbopmxjw.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gt2qqmbuwwn.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gt2bxpjgxbo.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2uywvovgv.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2nenfqrqw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gt2yoeeghnh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2qubqpskl.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2tgaktduf.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2fpldiknr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gt2itzoyphf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gt2zarawbfg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gt2jvlaiiif.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gt2nmetlqed.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gt2stckjoem.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2oxxkggqr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzmztiec.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gt2cyekrabp.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2wrxbmimh.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wysmybas.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2nrhzqmwi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gt2jydnsool.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2hakvqzgd.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gt2wqddhsni.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgvfhbon.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2agaeoqra.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2bkybfvvt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gt2aqtminjx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvkedswr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gt2kgejuwsz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gt2utvnjujr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2chouklvs.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2ladezbja.html


<!-- 参考信息 -->