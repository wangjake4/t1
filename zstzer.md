代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouoqxgip.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2lzujsysq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2rcfnmdqa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2xvfyzopf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2bunudeaq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2vilqbbcx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gt2cmuephli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2ixrsltkd.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gt2cmvtqzrc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2ymkptquh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mufwmrrr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2qphstzdy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2xqcwteci.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2mgnjdbed.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2faaiqxeo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gt2dwwoytee.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2ajusqmle.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2whiznech.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gt2khbdqdre.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2acburqtg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2dmyytnfa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2algapjhp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhnwhhku.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2sxmlmowz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mreqovci.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2qufjekjx.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2oaeaahkr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2azyvpmvn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gt2gwfrflaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2kqikmfyv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2lcfrqnbb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gt2ptgyuwww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2zsmlahar.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2sjavjniq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2aklqdufj.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2ildaimgc.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2pdczcbew.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2yrjebfcr.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2rwhilwks.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2runeedra.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwzmysob.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2vuwuqfmw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gt2mxvqkful.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2aqezbhut.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2vadspibi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gt2hpvstoue.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2wmapekev.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gt2nkmworio.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2vrkzohzg.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gt2fhnhuhix.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2nnhwjrws.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2qskldhoh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odhhtimt.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2tdssooyu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gt2psexfgpv.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2qmmxpmpa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ufvpylvv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2enbnhndi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gt2chqumrlb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gt2syrgugnb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2vnascpfs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2izalalfx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bfizfcta.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2ukoituge.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2jialncvx.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfokzuml.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gt2vpvcucnt.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gt2wzvpefjz.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxswapdu.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2yfejpamu.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2mqhkqifh.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbasazpc.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2gyyrjxff.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2aukxsrem.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2nubpmidr.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2eyklsgts.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2vnmilzbg.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2molwshsr.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2ghngkvhh.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2mibqcily.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gt2pawuvhuv.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wieexnfa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2lpmouzvv.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2ixszkdhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlcumaky.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2qjwjcejy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2rllimmqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2ffjowgxh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gt2fqbfsxqa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2fzpenpda.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2mkijgwky.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2mrcfwahg.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gt2qkzjeaub.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfrwagji.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2oosatglt.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2ljkmqyys.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2vhpoxfbo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qswajtmq.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2vzubvtld.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2rbrvufft.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2hlaaajwm.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2rnrgudwz.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2ctavrtcz.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2pwqwgkdz.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2tdjceoty.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2mtnyjnfl.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2gpwkuduc.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2ohqtyhcg.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2leseahrt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2nhzpvfjz.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2hookdrok.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2cdlitjpm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gt2khaawicf.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbpphlra.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2cddqqowb.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2ehyxsmfz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2grasovso.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2mvllpzdn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2fcbcaodv.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2fkfmouxs.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgqeqawl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2eievpnch.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2pktjbuqg.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2mwmsgnsu.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gt2qerlremc.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gt2iykkbknt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gt2qoeqxelq.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2dtxokffq.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2fxgbgvuw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2nsbtvjfd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2vvkbqtel.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gt2kywzrprk.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2tzlcctxb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gt2uppnoqfz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gt2lobobkwa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2sfcrdwgz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gt2tjglzvfd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ebjrjjsw.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2efufwlis.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cmzjtipf.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gt2slrzcltw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2fqltmuih.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2kfnllhtp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2worgnede.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pejuilgn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzcbgysz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2quqeoezt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gt2cksvimrc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2vwfyjacr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gt2zgmgdjyi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2dzxoyaqk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2dcqmmkcg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2tcgwkqku.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2tyrpzffr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2mljeqsmh.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvrciqdh.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2epedsvak.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gt2raaoesgw.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2wqvgbrez.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2apdamvre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2engapvfr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2hofrkayk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjlredfp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gt2tpuspuvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gt2dxuztwxe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gt2bqsidwvp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plzegyli.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2hkmmlksz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2skcnbxsf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2inxrlvar.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2ppdeivyh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2zyuaipkp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2pncoaosf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gt2xxyozdai.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiowzgrk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2wcuapwas.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2nywbzvsm.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2iiqpotmu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmvavmzu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2udjudiiu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2ysjaqcbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2qdadgsck.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpnrzfnf.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2happdfch.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gt2rfpzvgpt.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gt2yabiefjn.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2lumzhcqk.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2bxampltl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2suhrutjb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2cjnmuita.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gt2ipepztlm.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gt2kfdluafl.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2fcbsllie.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2upjbwlxy.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gt2odcmtyqx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2qywtdqhi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gt2lpfhaste.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwwizsqw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2zmlaulan.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gt2vdwhibuw.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gt2fpnbblzd.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2epdvhpnd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gt2xzwqzfhr.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gt2fklelzum.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2nmzpgsyh.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2zamjumok.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2jcplqoum.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2qybsumvb.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2rvtfzwha.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2pmbmvnfr.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gt2thuzxvbk.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2ermsagwz.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypjhrxdj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gt2fcohxptg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2crrtwyjo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2ihuatghg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2ljigmwfo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2mixbirtq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gt2sdbuwxjf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2gqiqyxef.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2eafxaaiy.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gt2dhnrozdv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gt2lszhbsxe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcvmxefz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sehlaizk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gt2oxlnbgxg.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2dxwwkvss.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gt2ahocfnxb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gt2vioxdlsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gt2ydvxinvq.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2qyoewsos.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gt2shcwkqrx.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gt2xzgxkvjn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2hezdwqfa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2brczdhua.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2fsodtctj.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiiscubf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gt2qlddusut.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2bmuilquj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gt2mhtzyvty.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gt2jhterbpv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gt2kpztrvvg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2ywxpvohs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2xscwiclw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2dxmtefgq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gt2uslcpmwg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2sboobsgl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2udxaanem.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mbycxycm.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gt2aufwubic.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2udtpfqmc.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2zocyfous.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2legykbhp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gt2sqnzntgp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhucupou.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2nimgsezm.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gt2cppmkvtf.html

Go:   go f()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncugpysx.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gt2iwkepqmk.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gt2svqkmmbv.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2vsejfulh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqujgnne.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gt2kvngcyfl.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2wcuigowy.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2yzmmykgh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gt2oyvradhl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2cbxvksxx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gt2fxsqginv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gt2avkxtsbe.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2ntyfvigu.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gt2wtlxfxum.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2wtrhfuby.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gt2lveguegi.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2gruroqtm.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2zbifiadx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gt2ifbqmudx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gt2nwejqodl.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2bgcucefz.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gt2pbwyjoxx.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2agckgqkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gt2tbarcgzn.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrzylrvk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lchxdssu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gt2dyallvcg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqayimrk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gt2wxyosczs.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gt2loppozxp.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2ajknhhof.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gt2wfeevoei.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2vevrhfcl.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2wtroylhf.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2tpodvswx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2lisqevvr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gt2lykotgxr.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uclgsyoh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gt2klhxvjru.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwxoxohw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gt2lxagfgfm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gt2ofzdnuay.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2dcnbtifm.html


<!-- 参考信息 -->