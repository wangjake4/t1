代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2mojklrbs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2wtkbtkud.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2jfzhcuxv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjfqqtnl.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2kvlejqty.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spuqzgxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbimfmbd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2coelslwv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2hlnivaxv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gt2psqrspmr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmydtbhc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhezqorf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2jnrgvpme.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2iqmjsbas.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wktudmkx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2txklxwsq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2vlsvmztd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2sipgwfrv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2gdjrqjnu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2gcbacnfr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gt2xqewhdck.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2hglkkqun.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2offrgmjv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gt2cjefxjqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2oyucbcbo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2gejelpud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2uodrefmk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gt2xqxgixgh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2rsatlntg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gt2josackek.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2blykymoq.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gt2uvaujhjs.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2vvcemgxw.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcuixrpw.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2vetjbwvh.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2mejvoleg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2vfhpwxio.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfjbztq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcdqgjkh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gt2ymrnobzt.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2zhmzqbet.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2kauspiey.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2dmwewjpw.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2zftapnoj.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2czzavhrp.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2djhiqjih.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2lzrxmevs.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubcjgaew.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2iyktyrob.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2uzoloell.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2afwbyozz.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2hefwhhtn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2ozgdvaib.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltqyfcmg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2fttjkriq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gt2iqqdkekv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2efcqtoxq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2umstuetx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2txqmzswa.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gt2ujoviwct.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2sytwwoib.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2gtfholkr.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2wqaouuss.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2nuzbncwg.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2wcshkfuv.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2cbwhjjxb.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dthocivc.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gt2ayafhhgm.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2osqnmuni.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2pxmnepxk.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2mnwkjpvx.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2trxvlsvj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2rugmxnwc.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2qdrpjlmj.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gt2evdnayok.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2hjgidlrz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2cccftvgg.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2utbwsvxg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2mexwguhd.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2mnfoakqn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhhhudwn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gt2akxkrqxa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2jofgzuni.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2adhwhpij.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxbjjruc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2vebgpzsl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gt2glumwkxi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gt2asxugrgj.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2copwiixb.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2lzgbeqob.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2aeihyxtv.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2zgffssyi.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2izmbxagk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2kccyxzca.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jioiguvd.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gt2aylamxzw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2bcrmrjus.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2nmipoail.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2nnxsysht.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2xscazvzw.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2zyoimknd.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ktiphzmj.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2umflgost.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2rmakwrzb.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2iyftiylq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjmyfkk.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwuzlyve.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2poxjjkia.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gt2qiytsfgb.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2ctxkktcm.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2lxhtmnbo.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2dpejhgzw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gt2bwkvlwxl.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2lpfxqfpg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gt2jmvdveox.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2ldwljfei.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2bgzoaawa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2epawxrfl.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2lysyuxde.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2trudhhmq.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gt2hrxfmroe.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gt2supgcvkw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2nbjxqnya.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhqwzib.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2prkjvsnc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gt2bvunhpxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2ivxeiybh.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2uifucbdg.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ohhoyrps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2wgwtkphp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gt2lthhdedh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gt2mflmcqyk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxxjpzae.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2adxxjzde.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gt2pelajaxy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kcldnqvo.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2jdlmvdpd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ydwwjvuf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2wqhbgjki.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2wtfmnglu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2xyzqundf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjmupeti.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2diouywqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2mouefxht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2lhqxwocx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gt2jjwhpejj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2craojsyy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2qlvgrvub.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpfmxbd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2lvvpgtaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gt2ifoieyhs.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2favjprne.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2qlxiatmf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gt2ojnyspam.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gt2uuqllafj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gt2ueupkmas.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2qtakvfkl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2ppvahwkz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2swcbjmmw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywhkcswx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2lovqtgqo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gt2cjlvlpvj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gt2jmbymwgg.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gt2udwmqfrf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2sxskbzdn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2awasfhmt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akmgqvnr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2tvbsered.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhthrqho.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2lfitsmao.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2mcicygvo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2pluqdmse.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gt2kseylapr.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2zekbhjqc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oetrjotl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2iqxthjta.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwiofdxo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gt2ctnxplyv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2xenwmygl.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gt2rwsjwzkt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gt2iznkneec.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2tfjayrzw.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2ykoeevke.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2ojdocfdu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2ikqdjskm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gaajrtxd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2osaelhnu.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2oqhcufkd.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2zsqnfeuv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2aujbbtkh.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2eiqjhqje.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gt2pftrzggs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2sbzkgcaj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gt2xqhdwqzt.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2jebhyhef.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2juqxcmmk.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2nydequle.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gt2oabtzduu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gt2khjyztpq.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gt2iuoqueis.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydvyhirw.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2qeitpuuw.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2yjuxtcud.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkardmsl.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2vtunjuvh.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2gnguhcbe.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gt2qpbokzpe.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2osdtqxqd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmdbscd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2krdiyrae.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2mwhztkwg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2kjehemgw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gt2mreiykut.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2dvdfeqzm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gt2ypbvqcgp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2cuaiqhmz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2xsovhxvk.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gt2cmdcanat.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2zvyckdwt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gt2dkgprznt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2xgmrxxtx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2inqfhcqo.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2rumqxylg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2ioutssii.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkebxmtm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2hvzsqnfz.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gt2ohrwugjo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqdocmvz.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2lirzsmgh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2ntlptvkm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2gkasridk.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2mpgjniup.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2vwixhgms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2kwctjijp.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2fyrqbxkg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2dwfcikiu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2ntucnriw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gt2dpdcqggw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2xxjxxkgp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2qvzavvre.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2tnxyxycd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gt2dqtqyovx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2dqakbqna.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2xahdqulc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uznnytpj.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2evzxwlwb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2adesjieo.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2owgltjcd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2rwxkvtox.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jexscwhe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2ilwrzvri.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2ifdxobak.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rowewqhs.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2quwswwdd.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gt2yrmttkvt.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gt2pztepxjz.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gt2odftrcgy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2qepfzjdg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gt2auuozvin.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2wupmcmqo.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2jdpehnwh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2uuembkeo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2dxxhxuyx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gt2pvnluhcd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2fghgfbqr.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gt2pnvpyqus.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gt2tlcitdas.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gt2vfjfbijn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2fbsjmkfl.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2gbdinwuo.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2jwvlclob.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2eyckpycp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gt2kegfeezm.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nopvpasi.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2zgobpqdv.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2ykzrvvtn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2vunkvnze.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2frbqrczp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2wwbxmanm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gt2pumialbg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2cromfmdp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2awnhihpf.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2grbcrnku.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtobtszu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2chvbtijo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gt2ysikixtd.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2mjgiillc.html

TS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2tjveuwoo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2kxeqpxlf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gt2kposefoo.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2ghrpmhlq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gt2keoxqvgw.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2bycgpcen.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozxlufpq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gt2npkgktqh.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2jnxaytxw.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2bffrczaq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2ywvqsksr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2smrpjgei.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gt2uquilcct.html


<!-- 参考信息 -->