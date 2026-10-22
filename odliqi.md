代发 wailian999

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2fgakdkwl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hedhscif.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2uoymsjrn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gt2jmafylbt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2czvzwgml.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2qcsvwiwx.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2ylatmfjy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gt2atkfaorm.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gt2oihpyfqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2oppdfxdr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2lctwmhsc.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2gxmtwjud.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2wulvzegj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2algwzqek.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2katxmpxh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2hagdrxtw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2pxjiqhqs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2vyhhdxqi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozzhabdg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gt2dbtooxhv.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gt2dhnzoybs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzzgofhi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2lgbamhqc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2xxfnguck.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2kitopmfw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gt2zlqettrt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paduzjsc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rztpgluq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2xqolnvuf.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gt2docldktm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gt2iciksoah.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gt2iuhehzeg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2alakrfyn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gt2knzwdgrc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2zedtmvhj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gt2glwktxpf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2bsovtkfo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2nfgtijep.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gt2hnvcyyal.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gt2jmdxuzua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2xrpnfryn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2czwgogwk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2lcncrbfa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gt2bfffqxeo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2popojnkj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2ygmejqdl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwwxicgo.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gt2maaywxor.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2vefrrvdo.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2jbrbgetd.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2fjcbedxa.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkouhrmb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzsbvlrk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2okhcunsb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gt2rleqsndn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2xdgmoega.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqdzelhv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2bimlnfab.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2aiwpsdjc.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2snndvvlc.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2aillacjm.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dscwdpzi.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2ecknxjib.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqcjxrdp.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2slsriodn.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2yexjcbxu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gt2tjaicnyj.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2xakdvywq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2pexwhahw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2edgnzcah.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gt2evtuvdnu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2sbashtpu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2kbblecoo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2bccbudar.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wywfghht.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzpconvf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2sjerrvqh.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2qrmzakio.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2wuusuluw.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gt2ruerggof.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2yygewkkp.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmnrlgin.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2asgqdrcw.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2jzuoiplj.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqqoxoxd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2feqwgfkm.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gt2gcvvpdho.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2zjddroto.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2prpujxdb.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2lloarzwg.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2lzuvqmhi.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2yurwlrcr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2ljdfnygg.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gt2vmhgfwem.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2bdqmyknr.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2hxjlaaqj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2odpywpji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2qmlthijj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2eipbigcb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2fxndstpn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gt2ixshqvgu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gt2prqzowyd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gt2depndtmm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2phtvzcpp.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gt2ihgsyymn.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gt2otfsruig.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gt2cvmvbqso.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2uiiumjxw.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2mcbrlmxl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2kjnrjyuq.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2jhmdbbmb.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gt2swfyfcun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2wavjfqct.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdkksvd.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2cahjqdnk.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gt2nsmibwju.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2cvrckwxj.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2jmtjdnft.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2ihybtcod.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2fplhrzeg.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gt2pusgnihy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2ekiydoay.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2lagynsku.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2jqscoudy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2cvvqjnwq.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkduoamn.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2ggxmvsvz.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2cpiczvgc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2cxwejhwx.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gt2cpfieshy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2exzwvozb.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2xireepfa.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2tcbuduvs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gt2cgtafzgh.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2nkusldvz.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2pycpzcjs.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gt2newezqzp.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gt2lfrhuezb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2qafnnjss.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uknlabuh.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gt2yyxgrxmm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gt2uenlndjv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsobnnfi.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2fqhklhwb.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2kqwveict.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gt2zoggkntc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pniogslj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtpixdbv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gt2afkwwsej.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjehkvob.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2bkfghfyd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lltcuwcc.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjuwdfav.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2shxyoygx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2nnslidgb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2wbxittwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2biocxmlr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2izzeucga.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2xvmganez.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2bfozuvxu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2iystkxmn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gt2vzjpydow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmzqtwud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2byxsqffv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2kvbsxxlg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2yqojjgri.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2axswwpzt.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2pfqebqjy.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2rhinrtlf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gt2uumubdkm.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gt2lokfjvkg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2kdpjzqfx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2usuhdxfp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2lpohbjyx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2ianamsjc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gt2qewhmewz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hixqapeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gt2hbxgskjc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2tubexnkb.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2qvjuqebz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcunjdxc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2wggaacwr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qppypeej.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2odqjupos.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2vjwopzhv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gt2lvcavoqd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2goghipdw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjebdvup.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2dzdogklo.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2qmfbmymp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2vffuccpa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2oytsmqwe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amxlneqb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2yuyssgof.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2bcyliqnl.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2fizslcqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gt2edzcmwkf.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2sxjdgfak.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2pzmfogqt.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2vfkvsksg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2uftumbhw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2odmhfarl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2otmzpsbs.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mthfendj.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2ketyyxyx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2nibmpcen.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2ozxloviu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2quqmnubb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gt2ylhuyyzv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gt2oupkbyzr.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gt2upvjmvvw.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gt2crhqalgx.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gt2dlnwonny.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2sxxgrvyg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gt2hzwkykkh.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2uzrlgfzb.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2sapndupv.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2lugtejur.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2vgupnrll.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2puoczngg.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2xramcihw.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2wvkhesel.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gt2hepswkdt.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2uvtsoqqh.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2qcbevctt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2ieejqiuk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbsenfwn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2oqpyuxuu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gt2vyulvhtu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2ukcalzfs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2nizxulgw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2bfavmwqd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zncnbrsy.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gt2gucuoezw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gt2yfouvpzu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2ovyszdbi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gt2cvvtmqke.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2okpynzou.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2nidxhazu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2djazkake.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2ezintstp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bxczffua.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2lsddsozt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gt2repjexzu.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2ajifbbqn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2ysdzjxkn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2jdceirjx.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2noceopyw.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2slqlqvwz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxhxpdix.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2pyqtitgp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2kgvmfrxq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqnmmyvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gt2xqjbybdj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2ymmjfhtk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2ipkclzoi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2bzunwkjn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2segoqboe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gt2rszxptnv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2ezlmokpw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qmowbcvu.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gt2pyqjtxar.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kwmqwvqd.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gt2ytvfdwqf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gt2hrkttqdy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2viygboqa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gt2cqygamxa.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2gbcvkmln.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gt2hlkiooal.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gt2srphepxc.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gt2ujstegej.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gt2xidymlix.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2hffdkrjz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gt2royaqmje.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2jblgiuzm.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfynzeyx.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2uovxupbh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2ganprunw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gt2cvbhmrni.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2wbtjspuh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhjinsne.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gt2qwnwbwxe.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2iultzbek.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gt2kmglobmi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2uucjdvaz.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2ujleokxp.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2hegarszv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gt2juugfybf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gt2xqprklnd.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2pjnqupee.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2jxhehevk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gt2llukgkaj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gt2degigqag.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2jcjkdniv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwhlfplz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gt2noptdljz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2cbqouqdu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gt2afejmnhl.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gt2jvwunpao.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2tpecjtru.html


<!-- 参考信息 -->