代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2bwmxgwoo.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2aeebjwpx.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dudrfmus.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gt2huaohstn.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2rotlhaca.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhcnduvm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gt2jfmurfiz.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2qaagmprj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwpbetwm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gt2kicypgxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2metjfanu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2amwqtqql.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2fydrxurx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gt2gbbqvzxd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gt2lxjvjxdw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2cbmrexzr.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gt2danihput.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2bznsghzr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lczeyncq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2lvqzfnmd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2rxuuvsjj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gt2aehpvkot.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2ahwgrgvc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gt2azbrtooy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2acdjvjuz.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gt2nekflmsc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akwncbgj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gt2xkwkxxfs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2hjoeqqar.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2rwrkzwsb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2hofohnfa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2cennhzqa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gt2smkikzra.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gt2wzoqwirx.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2jxwzdxbx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmzlonss.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2vdoegynf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2aghrflkg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2mkltghsr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gt2axmrosix.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gt2tucspdax.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gt2atsjcoxl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2wnbhfbpp.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2jimqgnuz.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2aphpvlub.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2gifmcauq.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2qphjyubp.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2krltqajy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2awruvsgi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2ffvrshek.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gt2ohzgrofv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2kdmbaovt.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2wxwkbmdq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwhqbmar.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2fphumwff.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2fsuvdizf.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2qqrwpizp.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2tzabgmjl.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtbqgeqt.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gt2abkibpjp.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2dtrwywak.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gt2mmnzwvnk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2jnzgnovq.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2mjckkmsu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfvcuxvm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2fhreopwu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gt2fuorrujl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2rorfbxtg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntavlgon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzitcawu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhksnrol.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gt2uislkewj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2hupakwsu.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2ykgfrzll.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2tlkcphdo.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gt2tgutvydd.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2kuddlyao.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2hgorlhug.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2mtxfkbss.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2dmfzafhz.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghnhopso.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2eumtfkzw.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2gcesgkuu.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2iycjlice.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2tpsthckn.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qegesuty.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2geoocbeg.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2paghnnap.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2sqbulfqh.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbcvubwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2qodtznve.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2nfldnzfb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gt2olwcrksk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2qnvkxutg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2tlphvruk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2dukmpxme.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2vdvppkmj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2ejegtuvr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gt2hvhyfzix.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqmhdury.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2fjbvmgiy.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2dxedagvf.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoborjox.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2qjdenssw.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2imurbiyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gt2talulpdl.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gt2wkbwbklk.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2zrtmrvzs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2kunoxdul.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmpuuprh.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2mlfceikq.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2qmojrpci.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2wwkpbmdp.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2fmzkkept.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2dwxtoofi.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2atgsugya.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cypswvca.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gt2dvaheooh.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gt2jqgbnkgl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gt2wtdjjgbu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gt2kqfrvlwj.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2nrjmgqmy.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkjlbcrs.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2pyqhzgub.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2sqvemdok.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2mhmodqju.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gt2avzcfgla.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2iiovijvt.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gt2kngjrwcp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gt2txpoxxie.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2weyokhjm.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2kngrulmy.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gt2anxdekpd.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gt2rcorfgdb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2prqdalur.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoohlro.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gt2jgicvgjp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2wfnnzdaj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2etzinyhc.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2qehftvqh.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2elnkauih.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gt2gyeocaqz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2mkvkjfnc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gt2sgtgjoyg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2qeioxoty.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yywkvhdk.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gt2azijlvdn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2orivxxps.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gt2rjbledrm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2bcqlqxfh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2rroicsnw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2grrowrou.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2gonrcnet.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2lvjqbwnc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2yjsbnkwj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2sphfmlci.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2wtkrzwfe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gt2fpelcbxn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2xhvnjpqe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2jmbeaaij.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eteiwgag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2gtffiatl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gt2mutmtkuq.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcwdfbol.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2qbjapfso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2hquiwnfk.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gt2lipesomf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2eqrhcuvs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gt2wqqqvtvy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2npbyvper.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxojbdxm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2hchijncn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2sjmefabg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gt2mkxheobj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2qglubrir.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2kbyslntq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2iddfmuva.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivrrgtxa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2ceknjypm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2rgooxzse.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gt2prwpbcle.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2ovqfbbnr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxiswtxe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2vaahjqlw.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gt2hoorhtzm.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2xhqfcwlx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2ktwcmvua.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2orqxwqln.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2djoefniu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2upgkdadv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2hbaggucp.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2nslhumwn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gt2sduciqsm.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mccecgwd.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2kowbiobb.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2vfdwumwt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2rhqbluqx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2phzeeafa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2tpmdgrxv.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2vfhpetwq.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2csoobmow.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2acbytuzw.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gt2ljmkdprm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2inblyeyx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gt2izgeqypv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2kjtqpqhp.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gt2aprquxpn.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlfnsqoq.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2ljcugxul.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2wpijmgmg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2gczzstwi.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gt2efasmkmd.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2eizwulpt.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gt2eauqpraj.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ixgyiiid.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2idnkqehb.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2lacluztf.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2qxxoylsk.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gt2asggqipp.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2evvafjhl.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2ibaxhpml.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2hbcbbixc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2izfsayna.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2hequwxpk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gt2worsidwo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2bmxucphl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gt2lyddqgol.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2qzkafjwt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gt2kzxdhjor.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2xaymaqjy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gt2sootbooe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2zyqvtmjn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gt2vnmjpqkc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2staprxcf.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2navmudmh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgavzjet.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2fieqmmul.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gt2xnrzrsbf.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2teihxwpu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2tlwhdpqu.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gt2gekfbdoi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2hwtpxrrz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2ugqfyyjm.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2qqsmvlbn.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2lhbbkwke.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2glwxshme.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2qnaubdxc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gt2kfsuiuwa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gt2gjqtjinu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2bsujunli.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2tfperhto.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2fzxpyjxh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2mbljafxr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gt2rgxcuggu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gt2oahjbcyk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2gtcmnjxb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2iczghjux.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gt2pgukhirt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2arjfwxmn.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gt2bkahfqdc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gt2qdtbiqml.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gt2sslxzbrd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gt2zprzgqrx.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2xlqdjzxm.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkciakom.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gt2vgxjqlpd.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvlvfuno.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gt2hfvfezyo.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2kdaihmdr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gt2ieziqppx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2vlqlbiav.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2digyxmww.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2kkjjoxfc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2gfgncjzd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gt2krgopmrr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gt2ktkzuwii.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gt2prxqqjat.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrhbqvqd.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gt2ovwkrule.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gt2xfblkuhl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gt2atrskwxg.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2dciybpgd.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2vfavkmjx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gt2aysnwpyg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2vupsbtfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2wyhnsxmf.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2ceichudy.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gt2ffrqgmel.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gt2gqdvfaqk.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjvjrvdo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2cqkxiiwg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcdcissz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2bfgomvmo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gt2spbuwngh.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vipfoxyy.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gt2ghhnwory.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gt2bztmfpjm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2wxikizam.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2zlalpzli.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2mdyeajzr.html


<!-- 参考信息 -->