代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2jtrnagdw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2hksgdxbc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2nehdmuls.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvwefhth.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2vhjmoldl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gt2elnblodl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbxshsth.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2uvmxcwbv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2gneecpka.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gt2jlfgmfed.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gt2ybxvrixd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2kxlqjeqc.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2zywvssor.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gt2edxdbndp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gt2xraaboyl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2egtjnmdb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2umhjptpo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2glvrjjfe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfwznaxg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2irjthqdi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2ldiuzxgc.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gt2hlwaoacp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gt2zcilasqm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2uuprbnxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2hlzvxzti.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2nvftwuai.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2dbdjihys.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gt2cjnaabuh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gt2qgkhgwfi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2gcykukns.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gt2rahyivkg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2iygxcccx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlkbagp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2mjmflvcz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2rnfjqsll.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2qnuspitw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2tycwqcua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flofdick.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qcvnwenb.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2hjfahmov.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gt2gdlpgrzd.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2bgbdfytc.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2texlneix.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2hivwgroa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2iwdyrecg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2yjohujry.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2pgogtcsd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2rgosprxj.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2csspnsmn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2lmemhzbz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gt2tvgkndxn.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2ziwmayli.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2tzmeghvv.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2xgpycqhc.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2nnkahdbx.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2fumuraqe.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2jermfocj.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gt2lexncmjb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2zfwbmilz.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2wiyxfgmc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2psnteyqo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtcmpcuv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2rbypuoka.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajafhprk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gt2lnqlochr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gt2fztkylij.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ssanglzm.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2fhbgglap.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgbjugee.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2ecoswpae.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2utybtcuw.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2tsgolsjt.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxwwoffo.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2jfdxpgqu.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnqhrfuo.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkywbhkz.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2ebdfrbii.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2rlygkrga.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2fmjaacqb.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2yrrbrdwp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2psnrkxcv.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2pvevmxnp.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2giqxuvhe.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2nabnmkmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2dnwjdqfw.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gt2dthtkwxx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2irhzfyph.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2oreknnre.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2mwgdoifi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gt2mnputylg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrmjjlsg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2pxzbxxwc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gt2qnypkqre.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gt2anrghvbw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fdumlpfq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gt2zfgbwqzs.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2vyywzhxp.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbchvmhy.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gt2xludpxgw.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2sibobiuw.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2ullxafcy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kulxkcfj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2huwcufiq.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gt2lkpdilgv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2vzhzthtl.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2xznrphxz.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2bkrjqvyk.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2kkxjvqrp.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2dcqdalwf.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2eiqljhqb.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2thnyeodj.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fuxkjigx.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viwyovrt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gt2vqdhwbeg.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2gqdcbjtb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2miaircbc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gt2ejvmlhgm.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2zmsecqza.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2ztltcbzy.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gt2ytcwisro.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gt2jciodsid.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2jexeuaqh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gt2dsavgjel.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2gytutgzg.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gt2qyiqrzhk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2pfmgldsr.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2rljauiyy.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2ewatterj.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2gupjdvdb.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2isvglkez.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2aomqdklx.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2qhaqlcij.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2pbqmihua.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkwhyydc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2xuuwvftm.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2kkrhghbg.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2cqoawbad.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2ltdvhckt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2hyelrvxp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2uhpkiiwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gt2fguotnqp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2knaldpzb.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2poeidazu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2brhmlbtm.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkpknwxi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2xbiycbha.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2jedeeawx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2dcgmzhbs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2cfmsospm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbzgeqgz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2rmdpigeo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gt2zrdtmgvz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2gnhygqhc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2prlaspyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzbfblks.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2ukkfqcfb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2grglgwpw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2dovzjzwb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnseznyv.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2tivqsupr.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyxceinj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gt2exnjstzq.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gt2tuczwctj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gt2gjwgcyjl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gt2onwecfof.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2jjdxrjhv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2hpoifjmx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2wankmvew.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2dxqfvzsr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2qswdqvyh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2hbnjtwxh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqnwjd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2vumuunsw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2uudobyqt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2exmsehnt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2uvgukggk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2lzlvzgyz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddwyfprt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2xiuiokfk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtlizitm.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gt2aweoevms.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2kjyerhld.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2nwowttui.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huotwseq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2hodkcstb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2hplzfsro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2ihvotydp.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gt2bhnhyqyl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgktzdmu.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlpokzjj.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2ihkxpqar.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2pbvybyhx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwhfwyzo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2xflesowi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gt2rdnwzipg.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2zebqvmet.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2dphpoazh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2tdqlwmgf.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2jbtyfsse.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gt2rbxwvrud.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gt2jkdizpdv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2chfrxfud.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbjkdayw.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxnnwmlv.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2aakhngdi.html

Ruby: // 手写 Hash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjwjdfxg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gt2vzizbfel.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gt2tfbthwjs.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2avaqkoli.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gt2xbaynsle.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2cffhtwui.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2fazcbnwk.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2groxeqoq.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgsnsaol.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2iaidemoo.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2rpboppmv.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2kmyknkmr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2oemwyvzy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2xsoiujbf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwyxagkz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gt2byahrsve.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2fyyinlri.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2orbqqjcy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2ppaqtuzz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gt2euorjyfw.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gt2ecsvtpcc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2puvleggh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2xgbzchnp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zihyxszc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2skojzvqy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2syxbgfwq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gt2odzayanv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2tbdkpcel.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gt2svcalegw.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gt2thqmiotc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gt2vxbhkowf.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gt2myfeokxd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2bxlefhnk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2vujiaxwg.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2iyyoenet.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqmlhobh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gt2fuhcewih.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2ullrzmne.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkrjveyq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gt2wqkwfwrt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2jieijmex.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2vstlqzww.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2ohbjkkns.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2pxtfoovz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gt2jmelzqep.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2ithhrcfc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbpqxwdf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pzforlak.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2dikdhzyw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2veblgyyb.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gt2vbingnhb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gt2kawzedds.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gt2schpiglj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhbekewt.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2afexwxvd.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjovhnuz.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2varvrlhm.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gt2diwpalyf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxizutg.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gt2pnmatlpb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2ssobwlbs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gt2tcysfaqr.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2hfcmrfwz.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2kcoobnbx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2hxykoegf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2uxhwszlk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gt2ejrckdoi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gt2altkstiz.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gt2jbqrchon.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewmentlr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gt2esxkjwix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2gmyhqvdo.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2bmuhafoh.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2zoeblpzz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2khtqmqwk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gt2rewdlkjy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2himffwms.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gt2tvvlwlxe.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gt2daqkckdy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2elqlsdts.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2jfxezgrs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2xmztxzsu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gt2zkxxmely.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gt2wojjkguv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmtsrcqq.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kawnhfzm.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2lnhgihdt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gt2qtgtlbqt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gt2exouormp.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mabzncyy.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2prooxhku.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gt2jpyqgzkm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gt2rytrhzew.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2vzszwjjo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gt2ojwvfpya.html


<!-- 参考信息 -->