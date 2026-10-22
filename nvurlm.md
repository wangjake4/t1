代发 wailian999

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gt2hpsnmgpz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2vgfdaqho.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gt2rizaufyw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gt2yzmduwho.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmwjlbdv.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2vrkbixrp.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2ifxinhxk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2jxfqkqbl.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gt2bsmqcrfu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2yjkdqqhf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2lykwnucf.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2xiukoscf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlvxpgge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2iseodbpu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2nffahjiw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2kuunkgdo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2lprypuii.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2fhlhplvp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gt2ueguvwud.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2wrdlbeap.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gt2gfcvrarz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2chvrjwpu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2raokhupc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2skdslxla.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2rpavuouy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjlzxvtk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2urwbortr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gt2gxezhpjh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2ccvqbbsi.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2rtajghtn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gt2futekgtm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2nhybcuuk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2bbvqatil.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2gvhursqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gt2vgocdanm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2ipkpkxhc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gt2qcqhntxf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2cxjhrxlk.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2ahuqzpmd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gt2tssgikow.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2uqbcamkm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2uuyajpqi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2ijpbqbaf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2duyfpjoa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2ghjyhfel.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gt2pbclevrc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2tbtppfop.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2ukrqvbli.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2pozljqch.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxonzgnm.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2pulfoiky.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2dzhnuets.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2fasggmgv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gprtfvhw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gt2csrimzju.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2abnvqvha.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qefkzrmj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2juyzfzbr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2vaqpahsa.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2frlotrug.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2vgdyswny.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubrssbgu.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2abgyjdvp.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gt2mdpgixtk.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2cbyjjxty.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2bqdhioda.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2qciddtbm.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gt2gffdeuzb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2ilgvckmk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2rbolgtel.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2mpjauvdl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gt2bmgdrnmc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2ehtjlkar.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2vymmpryp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hdpipswx.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2ptbgqzrf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obokouvk.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2zieojygm.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2vyfmdyjx.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2svaiebtp.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2qwsocywb.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2xffhgoiv.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvgndpnc.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gt2xojtrqdc.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2xxdgiprc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gt2iqskfpsr.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjzlmoux.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gt2yfncukay.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2hpqvxxka.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2qaslovtn.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2zdzhvjaf.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2rsasjndy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2pftxbezs.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gt2dkdyevdp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2jwachhzw.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gt2jvaisosj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2iwzajojx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2rrtmjrfr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2lwnzrmjk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2jinndquj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gt2anmzbrym.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2rfmiurcz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uijckxdi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2ctsutpau.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2rorzjzkj.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2cfroufiy.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2uvhzdofl.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2eimmddxj.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2gjovrtlm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gt2hadxexmw.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2yayjktai.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2oprermhu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2fhlsfjzh.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2wsfvyuvv.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2hyttlsxp.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gt2jhvrfosu.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2pujiyjnw.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2aqpqghzr.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2rlrkvzpe.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnfknnaw.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxoetrqn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2mtwrpsci.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2hecevdcm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2cdaoqlot.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gt2puhyfznt.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2znlhnfig.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2bvhzrxwq.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eixozhop.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2qgnlkped.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gt2idegmtwz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2gqrrzovt.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gt2bbovulhf.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gt2wagnxhha.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2rtwcrfje.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2wxkfkvje.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2kkywlleq.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gt2qnqlnpgs.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2ttewdefe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2ctsalrdl.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2npjhafzc.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2bltaicjo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gt2mhubpfzy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2waalbima.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2xmfuvnwv.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2fgeyitvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gt2hivlppeh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2rnkpzufz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gt2hukbjtri.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2ufbxtqpm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qshtufmm.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2tttbpdfk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qnhtpgxb.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2qkxuoiqy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2rgazhrzx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2ttgijena.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzytyrjg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2svadnsno.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2dxjusxkq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2xnewdpbz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2ccrzzbsy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bbwevexk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gt2ookmkjah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2lxazjdys.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2dqqocwzt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gt2zzpinawo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2tarjjtdc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoolrjj.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2qjnnkyii.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2xwgtioey.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gt2begqrtra.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gt2uwcnxgon.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gt2fthlaemi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gt2xwjfhtei.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2nnkoexii.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2mjvkxiwi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiklffzk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gt2zqwvqoer.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2fzpeohls.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqljjhmk.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2fidkhjro.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2sbupbhdo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2nvmhzinv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2ifcwdpdc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2ifzfgoil.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2lumevkfu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gt2dnkbwytn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2eejtntwa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2dryidbur.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gt2jmhsigdp.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2ludthsbg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gt2dqoujylk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2zjhlectw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvqilhdm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2sblxsxpb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gt2bcourvxx.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2stvccpkx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gt2uwdnrbhv.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2slejnlad.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtxzrfi.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2jmrgocah.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2dpglnyaq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmwrsspn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gt2uridknct.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2lbjytxed.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2ioizhtrx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2jmdcrhjm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntaksrco.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gt2ncannzpm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gt2dnjnqvfv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2nkpjmpfe.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gt2ldbduwtr.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2dmlrqcym.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gt2iirrfjfo.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2mjfmhpfw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2ccczvoib.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gt2bmkbzjhr.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2gdnjyyml.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffvpvnxn.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2xualprvk.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2kyyjyfyl.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2vgxwdqmd.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2xsylhwle.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2dvdldzub.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2gqduefor.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2rotwczqf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gt2mhzdazxb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzsmbrze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2dpotbcuv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2hycwbfjo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2qacbyrul.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkszafwb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2vvcdutfq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2fzmftahj.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2gslorgvj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gt2znbpumlw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekviociu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gt2xgycbubt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2wbivrqrw.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqiuxoei.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2hvcioxjd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcpdfhid.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cueibkjm.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2kzxoogwt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gt2vhqmuiii.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvottyxz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2otjaytpe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2yrfdyfoz.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2apqjtkim.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2uztajueq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gt2tshfvvhc.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2zujbxktm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gt2puzhqoss.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gt2xmewnmjt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gt2lsqzrzri.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2yosddxgv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2zqimunxj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2zbeyaqww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2kbmhheek.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2wuwxzrwt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2nkgscdcu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wwbwmify.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gt2zwxvuiba.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lvlifpgf.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gt2zaslzuaf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2splofjuy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gt2lxfutemi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gt2qbsjsofs.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2ucmibfgl.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfcxnzxx.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2hosshyfd.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gt2elkyjxyy.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gt2gythzrmg.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gt2zvhtzygm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2garisyem.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gt2qvuwegeo.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2ptshivxv.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2kmqmzzkm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gt2qpbuztkl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gt2trwksgor.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gt2kyndifvd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gt2unihvknf.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2gukcrclm.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gt2zrvfwnpv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2lhuopmke.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2pxmxozog.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2qrszfgdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlfttvui.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gt2cttbjqey.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2pxbqowkn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2mehnuqpr.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gt2wuvjzras.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gt2zagzdkkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqgturbo.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2rzofdhkz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2iajigvvc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gt2ugvdlimf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gt2paohgggj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gt2fbmnqnfq.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gt2sooztlji.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gt2gmvekxxd.html


<!-- 参考信息 -->