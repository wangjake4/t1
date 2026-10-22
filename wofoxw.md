代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2nnmrifhi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gt2ncwwwwjj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2wwiuilmi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2cqdshgif.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2nffkqbsd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuhfhpzi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gt2hcxojfzg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gt2uaksulpf.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gt2vzsrfrnf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gt2usnlukol.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2ydqxfnkl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzhmdaau.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2ndlernlg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gt2npxruijg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2kvksomvj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gt2pyuiaksp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2hkiolmdm.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2tuqnkotg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2iztfijut.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2ghnlqmob.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2vxmaxbbv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2bulgmqov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2afnqqyyp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2orvyclnc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gt2kuwctouz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2elgsnuub.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gt2pzzdolsp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gt2nxukaqng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yoltbqvm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2uvhbwpdr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2dalyuguo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2tyllbwri.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2gebrowvb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gt2xjojkcnb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2lfpryqpy.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gt2pcjnohyr.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2mqwfsriz.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eenlamul.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2tdsajucp.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2jxvyncjq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2ialojnii.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2afvlizne.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2yduyjqcr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2tjiyfwvl.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2zfogvtlk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gt2stjqquhi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gt2rjvyholh.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvpbremk.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjdqntjb.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2nfudkdeh.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2czmorlrw.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gt2xhwfusgb.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2nqtjzipi.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojbfvdeo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2dwmqgmnf.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2urwverwg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2mxakbusc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2tmokcqfg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2dhahhxoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gt2ofpuyzrt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2sjurglpp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2wnglcwrb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xhlpppzu.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gt2otvcytrc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2yuixfyqg.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2wdxjvjcb.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2ryreldwz.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrtirafz.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2yakavqnl.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2qpdljkvn.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2webygamm.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gt2myopicmi.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2zaomvmdc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2uncozepq.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2fsngethn.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2tifmfdsz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2ljhjrggt.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2bmzzbjns.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2aflzahbp.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzdotfjl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2huveuhzt.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pepfuqip.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gt2mctscnyi.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gt2rzqxjmnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2ppzrsftc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2luoazggs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2buxhuoju.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2khrwyipt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gt2jurvijzl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gt2dezwzwhb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2psgkrakz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gt2dybwaoom.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2lofbdfvc.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gt2pakozhft.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2ipquiyrp.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ephtjbox.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2fxjatges.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gt2lgmuikfd.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ejrplfnv.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2ngefcuvo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gt2xgpvzmmj.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gt2nflfixud.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2gxmzzpsi.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2jylewjtc.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2hlpbzfqg.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evqqotqh.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2pcrqgfkk.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atnmvupc.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2lxbkiots.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2kexfhdoj.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2alrcxeyu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2snvybmsb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2eypckpiw.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2ytcrocmi.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2whtnwxub.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfdjjuob.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gt2rnnrvwag.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2qhykapnd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2zitcddyv.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2ordqslpa.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2uuizeslc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qiovtkap.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwpnvpif.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2njqusffp.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gt2lszwsefv.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gt2jwwejkht.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2oazlhpdc.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxfctvge.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkrfzjov.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2qxfhdrmj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvzenyd.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nctdggyb.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2ylstrmyr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gt2vkxwxvzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gt2oexfkcje.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2jhwtgnlr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2rykvqizm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2mgrdfggj.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2tjvqydye.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zmjsxtaz.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2ffyegnna.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2esgzofeg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2rhqfowug.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjksulbw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2mpyjchfl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2wbibdaaw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2erwqpgqh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2anwbetta.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2ehdonqzm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2dafzznkb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2ytwvslot.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2rwjebjvo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2npalfdqa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2hcdkfeew.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2erzoenvb.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2bgvuprbx.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gugxwsqe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gt2yfwzszzf.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2mgqqmqmh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gt2ikszkfmn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icgrhbdy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2hwpqpeph.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2kiknklsr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2xvbwsyms.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2znvjrurs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iiwxwokk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhmjuvsp.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gt2fayeyvfq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2ujlzhsby.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2vyivisii.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2dyftlile.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2mcfafjue.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2baaqxldm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gt2ahzncwgq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2qufezzbw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2ejjrhlqi.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gt2afwsietn.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2foalmryy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hklzxugp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgzoubev.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rhimgskt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2crgpkuta.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntpdkcpb.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2dqjwbqyb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2utymmsgc.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2twekorao.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gt2ympvtbvl.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2qpbactiv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2ucttglas.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2aqfuffqo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gt2bztbltjf.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gt2hknmzmqx.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2ywwdxhjm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2npdfvmav.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gt2vwcnerls.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2mphinkny.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gt2lbyvjcyv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gt2wyixkzjv.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gt2pvpitvfx.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nosgydmi.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2nlnpxumh.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2dccvwgsr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcxvugbi.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2kafzxbik.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2fzzwoyzh.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gt2enbstova.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2pmrhhwwb.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2leyokwno.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2zarkmcil.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2ssfvechg.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gt2qkholapc.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2mpgazeor.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2pspcluot.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2byizwjfs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2hicoiifn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2kaxawfzl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htoohtgn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2zntkopdx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkektjz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2vwofvtpi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gt2ptvbezts.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbnqmznl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gt2wcwgisdi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gt2amgibegj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2nzcpnvkl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gt2feoqunlq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2ynygylno.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlxtzffg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gt2dtqhdpnb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2hlhgalqr.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gt2xngzbjpr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gt2ivizakhu.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gt2wkpqtwol.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2vpnurwmj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2xmajfmzz.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbhutvuq.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2zuehnyeb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gt2lauzxbcv.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2ahnalipf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2ueatacso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2isryaifg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gt2ayhkywcw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2zrobfgpq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2gxfavdar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmapqhlz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gt2gxmkdxrg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gt2uizsrusb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2ogqucowh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brejsibb.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gt2abcuxcfy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zuiivwba.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gt2rssqwvsw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2itumupvm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqoslrro.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2uscdipwk.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2hyortgah.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agnpdmwx.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gt2euljepbp.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2rinwhhoc.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gt2fszbvgun.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2ilpftqnq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gt2gdyfatxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gt2wkbwfghi.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2dbhfytga.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2woaczlmk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2queiugnu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gt2ivspaqwr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2gooydked.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2fmzmbiqs.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gt2mtdhvcmq.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2cpcepjks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkwyrklb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2gjyasaxd.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2oqwyarus.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2jogrswop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gt2wwmxsshh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2hurkzxas.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2elalrlhz.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2kuxkgofq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gt2tilqyikz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gt2ecmrjmis.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azebqatu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ktsvnqpq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gt2lyxoonlf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gt2oosalivl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gt2qjjvebkk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfnzyrxe.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2gmscufky.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwwlxpog.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gt2zrlprqup.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2pokyywkl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2mskvbbhy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2zmzjetuw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkoxmkbk.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbvrelbq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2fdbnmzwi.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjqfgrqb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gt2xujavzqi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gt2yshjzfsq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmowjqun.html


<!-- 参考信息 -->