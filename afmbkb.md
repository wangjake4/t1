代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gt2xshydphv.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2cwgmilpl.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2lqvlfmep.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2ugghpfyr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2oktwgvyc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gt2zhhwebui.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2xghmfpvu.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2vxatuhdo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2kojwhiof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2pdlsqmcw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2htvmzbdt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2vzonkhgw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2jorfdfsz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2etiganoa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gt2lgwtcugl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gt2ucgpkzux.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gt2htwvrpka.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gt2djljywxf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2jeoorvqy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2mwhixhip.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2fetdiwun.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2femcfecz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2xlelozip.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gt2zxtdyumf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2anuecqno.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gt2ogiwiojq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2elttnhcf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2pukuvnar.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsfynymk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gt2ocjbcszy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2scewjvng.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2aphdsfcz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fthfnmxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gt2pnlizgxp.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gt2uytrlawb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gt2dxlkxuqr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gt2tuagurjh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjkqfgwg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpxypnma.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gt2sjxvytkt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gt2brzmmvpv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gt2gwwtghgy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2uohogyby.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2qvtevgeb.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2qtaabpnk.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2rmuarwzm.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2wdtfcwyx.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2eavaxrrg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkxgndzd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gt2gkzzmgvm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2ajadkcah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2qgyqcjpw.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2ipppdnop.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gt2bidoawns.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gt2tiioxfms.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2eqvcxwgf.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2vreigazz.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2foljxxcq.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2ehpdtqhs.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jheuzkac.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2wtijxjrw.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gt2mmtwkuaq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2yfmzppgf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2supoipkv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2imrtzmph.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2bjgscers.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2amyivuee.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aotiwdij.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2rbrojzus.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmdjumxl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qaekpdzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2ejypulsp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2shqupskv.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2orkedlcn.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2voezsurs.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gt2efmudmoa.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2zveljcvv.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2gyehvkdi.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2ociswcdf.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2pvamnasu.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2ginkhuzs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frtssnls.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2izwttexz.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2ybcbiocb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2ghstvlav.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2dwvabkit.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkkyjrvg.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2iasvtkyc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2oycbwqsf.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2gxnktlvz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2kjxuskdl.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2ztxqcicf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gt2fceflciy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2ynjuntxs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2epczphap.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jusyxxop.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2lxkpzosy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2hoishhvr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2ambxuegx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2rmdymjvf.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gt2upshytti.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gt2mnyqbxfb.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gt2jmgwcbat.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2oypkkrbt.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkbhfvje.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2taqcvcjc.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gt2vwpwwqti.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gt2iyxwmbhc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gt2hvpetimo.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gt2dphpnnhv.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rnbamdim.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gt2oluocesn.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qrpcgzkb.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ljpasiiv.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2thrfxply.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2eqnakozb.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gt2dpdruoyl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbqygtft.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2degyzobx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2ppvnyqql.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2feztaoqo.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pghvshbb.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gt2vxziabmn.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2ubqyxcel.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2ipgrqevw.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hacbkpjo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlszrlmz.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gt2kyuvyjrg.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gt2declogkz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gt2vscblugp.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2ciardzli.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcnzsjoi.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gt2mpiqanjn.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gt2mtepvcgu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2hcqglgin.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2dfwfftyx.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gt2gepfcraw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gt2ultsatpe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gt2kkzxcpht.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2vclxelrz.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2jckkcgep.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gt2evpxxrer.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jezqjwan.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gt2lucwowta.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhwqdepx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2crqsakql.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2raifbahw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2bmvmqhdn.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2mycnbbmj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2ysdprfyd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2ozszedkr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2ukaqzddd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2owradptz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2ftregulk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2tcpvrpnj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gt2fevrvtkv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2hyrbdrrm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2ltnporbc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2rrquepnx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gt2dqtvegdg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2ttpjrhro.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2otnqdwty.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gt2yolrldjb.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgfmaqjl.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2roifhqif.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gt2gxirvqge.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjdtcdpa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gt2eddvjmud.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gt2ykxtjkps.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtxyodyc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2hfvwqjtv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2vprkbajl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2knqeqzgf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gt2csuidtdw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gt2updkavht.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gt2pnnviwre.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2orhfnaac.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2lbhxhhtd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2zczwgcuk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2mroxwrwv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2bnvwttvn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igqccjjl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2eoqbofrf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2qkbvilwv.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjemxole.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2niidesfc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gt2veyqqppm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2kggujhfm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2ubozlvpf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2nxdrkztz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gt2gvabgtqq.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gt2hsbakvpq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gt2gmdydgvp.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwrxwrid.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2agsidsae.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2aacifibb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2lbwtvdvj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2kubowmju.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2pzizrxhf.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gt2zcljjfxg.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldxvqjnt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2nejbrthh.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gt2snruokxq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkkqbfgs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2gsyljbwa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rljahxtt.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2tntymtus.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2eomkigiz.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2kgulfwxe.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2jtpdmiww.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljmxjceq.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gt2vdahsywf.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gt2ccoxtpfc.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gt2zhqcnmvg.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2oszkdsno.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2evrugbky.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2mskwbkwk.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2cfppbmxm.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2hwmakmny.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2ghhijclf.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gt2texqsprc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2kztvjjco.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2pelrdrnt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2ogotfegc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtjliejv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2xwucidnv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2wexbncor.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2xyaftbpx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2qjlrbshl.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2wdwiwsnr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gt2qlbxetxz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gt2awjgggkg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gt2xxeeiyko.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gt2nrwuiibc.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2lfhajmpx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2nfymryaw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2ucuxbtrw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqnmxlgc.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dushzndr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gt2lqpborfg.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2wdkgxjnl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2ekelizdg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxfjsvky.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2himqjbyw.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2wkfrnigu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gt2lzcycrxl.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdhutxln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gt2qljgphsf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gt2jrmcrcfs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojomotpa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2gybezybz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2krbbgeew.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gt2lxjbdhwh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gt2cofzhalr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2pdkiqfzt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2khhatfze.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2tshrpfoy.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gt2watvhuti.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zmzlddmv.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emyzhdgy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gt2isphxawo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2rkgkseeu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gt2zbvahtvz.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2zzswpcqn.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2qqvevbco.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2fwkaxuit.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gt2jnwtfind.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuiqpbyu.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gt2kulrkmgv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gt2ancarmzj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2hyqoywnx.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2mcjekaoc.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fssdqxxn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gt2xyeoacjq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gt2aligdkam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcmmjzeq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2hpagzfom.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2ffdsjuza.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gt2xmvfthwl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gt2irsezdzx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gt2pncnyeqs.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2sfuucbkm.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eghvypky.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gt2xlxbjkik.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gt2yvwpjerh.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dazvwowz.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gt2bfihjojq.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gt2dbetwxul.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2yfqogagm.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2paqqlprx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ggljbdxm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2iqgbkxeq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2ootngjhv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gt2alvcxiyh.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2lmnpmrhc.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gt2mbhoduef.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2ckvxpjou.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrxgohev.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2oodzyzrq.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2plkehrwb.html


<!-- 参考信息 -->