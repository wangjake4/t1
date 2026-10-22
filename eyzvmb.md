代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2nykilruz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2otoaxvpi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2pikurazn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gt2jrdjithe.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmkfunbm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gt2bhdnewud.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2pwbriqla.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2yfbcuflz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2gdndrpcu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2pnjruvcb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2igeeqcvc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gt2cydyzuom.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2jsgoahup.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2lcntfgcm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gt2pikkfmsq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2muxdsifq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2ueopbsam.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2ndmcjwkn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvecxiln.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2hxqwscla.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gt2khbqbtze.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2ypsnkhqg.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gt2kbwjriuo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gt2fombxpfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gt2qgmnaozu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2bpcbdzay.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgfzooqe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2ykwpbfeu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyaaopzi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2pacdupxi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2vkulfdtr.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gt2rpcrgagx.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2ufwrzdyr.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2xcynctnm.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2pltkvged.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2xrwuaxjg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdhfhjbr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfcabgys.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmumbabv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2nsxyfqma.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2rqxkffji.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gt2rfwzgeft.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsqgeddq.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2fvwuuype.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2gaeaucaf.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gt2imzbvbfl.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2axnhhsdt.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gt2akvnkcqt.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2ywpncnwz.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gt2jllsvbgc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duafoltk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2mkwiavff.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2ifkkqviu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwozlsqw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gt2ioqngclh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmyffeci.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzfvlzfy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gt2lduhqbdi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rnvyyzst.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gt2xmpmcwlr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2apsqhpvp.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2uwbasehx.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gt2kplkdvak.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2giilhwvm.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2ehoshdiq.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2bdbwofld.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2jvobrdqk.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2ffpmdstr.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2cofervhp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2mhctomdc.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2saeysyqy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2ypnvbjou.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2zzdzhhzg.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2dcbklyvx.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2dqcrgsbf.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2klzlrnch.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2pzfjiovh.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gt2obqnwhfw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2lcvdxmxp.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2rqjrrhfa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvanlmnp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2zrvxpkss.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2pqhsaqii.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2lkdqyqzb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2ofaahzfg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2nsqplcef.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gt2kbuqepsk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2lumjypmm.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2endzdvlh.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ruuiyvic.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gt2pxiuphse.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2xkqtdxaf.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2cceyrscu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2ctmrscem.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gt2txhkxhwl.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gt2veygzvun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gt2qzerdsni.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2zxxhmwuq.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2svratkht.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2dblsawdo.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2pvcjsdqc.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2tzuiquip.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooyvbvgk.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2qnsiucls.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2iiazusqe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kblosjsn.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2hccsqeet.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2tkvtdbjm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2ieszshmo.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2xeurqtal.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2chkrkvov.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2rutbjfsn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gt2pqhvucch.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2jkdfnkxu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxpgoufk.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2uindkywv.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gt2zukzgqjg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2tafkhkgo.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlyxfbs.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2tcusbuot.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2mmdnxdrv.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gt2crgnjpvz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2gjpcgtga.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2kcmbohej.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gt2clcvokap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gt2btuhuoaa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2pndoqzsp.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2vrvsjdhj.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2rmvlmyxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2txoailxj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2znnhrnvs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gt2jhqhwkld.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntkdglah.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ktzbsywf.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2rasveeoh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2isamgijs.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gt2jzbvqrct.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klynficd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2tzevcthw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlhfixql.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2bqhzurga.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paztnvfj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2byipzeeb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gt2rmqcnokq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2hfwvwddj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2fsafpxes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2kqzwmrji.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2vbropmzo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2uptypwsv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2cevybude.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2unsaiezb.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2nriawjzw.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2ejnnayan.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gt2ybmdbnuk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2rewfatzy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2ohdfobgb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2ttjqbmtm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gt2mkifnmlo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2qypeazen.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2vkcvremm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gt2ajtigszj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gt2ldbmedmr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2kkvxejsr.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2snvrpryv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2yhktpdsy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stdsrbkv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2bmmobyft.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2hiifoset.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2anckkkxq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2krbticmb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2hfewhqrs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2alnpuoha.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2kusjkuyu.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2wgliahps.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2zqzivbmq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2bakoeigh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2jyqltodi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gt2krqvstqj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gt2uuqtfvrm.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2zzorwufq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2wnayzmer.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2unylsdnt.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2hejvgxfc.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2oyxnelfg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2kpnvkuyx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2jortitss.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2pexwpooc.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gt2azpwypfs.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gt2djvwbrhz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2rxwbjdel.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2cvrtqsgk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2sqxhyenc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gt2kjklggcu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gt2htdfzpbe.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gt2bvvpfmvt.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gt2eyoxvzvu.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gt2swntqrfg.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gt2axkiebda.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2hfvettqh.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gt2tbuopmaz.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2ryxkwxox.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2otgqmkpi.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifmammcv.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggsiwobv.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2iswwqlkq.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2uxttsulw.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2rimojbkp.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2qyentugo.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2akfblsyy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2umttagor.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtuauqly.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2xdonothf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gt2opbafwcn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2etsjehup.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gt2rjrfnkqw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2crlgpghl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gt2xfvuuipl.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2uwwitxhu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gt2xutylrpa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gt2nmtzpzhi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gt2oszpuqyw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gt2yfiqjesw.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gt2zntikwlp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2gxwhinbb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2oodzdebc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gt2qeltyvgs.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2nyjistfw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gt2mlsqqjmf.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gt2pyxfuakp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2vreazhvt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkhydqin.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2ulwcqncn.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2ecklespw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2elqaufby.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2hyvykowg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojorncnw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2amhpjigg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gt2zsxcolde.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2cxbyimlz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2ogahabvc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2teuzdkcj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2undrelsv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2tqskfuxv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2xnnoqpkw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ubmgyuoq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtcvhnq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wpubkgxw.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpccuizd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2xokyfkyn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2krrlbyxt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gt2hcighjad.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbaezjyz.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gt2aehwyksu.html

Go:   go f()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aihufekb.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2qderjbhi.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gt2imoozryh.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyxtygwj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gt2cdkhzzrr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbqvpbsz.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2rbhjagni.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2scnlwpfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gt2kitbmwjd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gt2isonowbc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gt2fmmdlmzv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2bearmebd.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gt2toghihun.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndsqirhi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2mfogdqkx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gt2shwvkqqw.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2xomvkyia.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2tvaketul.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gt2sdawaavg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gt2iilmgpkg.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gt2gezloenm.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gt2woruyhuy.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gt2roiymxax.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gt2emtqvldk.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvurmomk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2etzamyat.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gt2ndkpnbtj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gt2rcwoppaf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gt2rjvrydzh.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrufhxxa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gt2nynpfhse.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2ormvguvg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gt2ipmihkgw.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2swzayoxk.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2iqzrpbii.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gt2worbwcxq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2tvgijftr.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ormlbdqy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gt2ewmnylyp.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2aqopjcgn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2xaktqgii.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2rrizrads.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2anfyyokf.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2okxqaorr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2xlnxpuko.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gt2slpinxfq.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gt2nmoenjun.html


<!-- 参考信息 -->