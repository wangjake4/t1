代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2dgrefkat.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2esnbjlot.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2fahroone.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2tnbnwxbf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2fwezkrfz.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2myuoayei.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2yruquczd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2ngnaalhu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2clgzteir.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2ycdrqetm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbavojwg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2fewaamdb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ollmqfvq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gt2tszfmglb.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gt2cuxicixj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gt2afbfaevz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owlpfuvr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2evshfgim.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2adprwlem.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gt2pbhdaezs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2wojzorfd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2okggtiim.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyehkjqp.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2fubjihef.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2zgxswlds.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gt2nfxzddid.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2wmofeafc.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsbnldwl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2panufdyh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gt2lkmrhonl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2mvhbihxv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2yxxoiqer.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2prrktlqs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2pjvykxew.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2uerhjmai.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gt2qzdqauqq.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2iacervet.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2olbzieba.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2bcvyeezp.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gt2ajkekcep.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpycngqr.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2nubzwpnx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2scbjbxeq.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gt2xunanbwy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2narivves.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2ecrsqyen.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzvvjwaz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvghfxou.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2btwuicff.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzuldclz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bbajimtw.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2bjswffnm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ckcocvsu.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2hksrenxc.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2vwnqftdu.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2gxnythbn.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2jmxkxnlt.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2hsnglgoa.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2jxcdkgqr.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkvucgbt.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwpsboyq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2pixaoely.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gt2zoihtlwl.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2lldwxlgk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2sujrhpfs.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2walkedwh.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2exxvfouo.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2qlvtiesy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2wvboquce.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gt2wpigizab.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sawznwxf.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gt2lsgtvkwk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gt2etztvfsj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2emtrqytc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzhlfqlw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2rsdxcggv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gt2dadvkngb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2tqgsjtfc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2edpjytpq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2xrlzpxlx.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2qplungrf.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2anbcajwd.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gt2kandusjs.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2afpxddqv.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2tcozznhm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2mywvlkaj.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gt2eezbypdl.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gt2nuatidpj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gt2voimmlir.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gt2hhejgvzb.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2pkqliuaf.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gt2adobxkph.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2eihqyovn.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dyplarks.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gt2cdqksbag.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2zcufxzhv.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gt2yqhuatwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gt2vocanyfr.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gt2kuiaokth.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2ktaztdii.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gt2xnkcscaq.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2lvevhrgv.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2mqywuujz.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2oyfektdm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gt2qsnbpdws.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2niqztokd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gt2ycjffcyc.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gt2mukfmrpa.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2ggeiinrc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2ayexwshe.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2mhakiibj.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2ufsacgqs.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2nnejnrnq.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2gluqwlbh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2vdsnkyeh.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnxxhzbj.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gt2hgdgwvox.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2akhsaawe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2jjjlcmix.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2rvajvnhd.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2zdjqkjyv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2qziaevld.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gt2poewhwbu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2orrgryym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gt2zyqvfmon.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2qobrbcvk.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2sspapaig.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2szdjcsqa.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2kbnmvnzu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2hvhjzidk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2fddzthsl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2pvrffepm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2inqagipu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2ieyhilgl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2nvhyavco.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gt2snhmjlvm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2yafuchyy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2ffyxvkac.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gatqrohi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2kypmsifu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2jvankwrt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2taesfleo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2vbymkqwb.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2thzmysqe.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2zwcgwnoj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2sdzbpmcf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2zzprbnhy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2sxlryjsu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gt2zwotawcn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2ldokmjxh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2mcygqyek.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gt2ifcpncjo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2dersmohg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2txjaxjvk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivoajzdz.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2rnqjxcln.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2rvmbaiyj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2bsrsvlef.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2gcuhciye.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2pzhvofsb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2tsesmbfw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2fwhxwtce.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2zesmkhav.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2dufrnjwh.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gauulxmy.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2wbxkhnyy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2klqzymws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2byztcpvp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2kibleldp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gt2ygkniaqh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gt2ftvcsjah.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2wkhvsmqs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqjmlyea.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gt2zapqxxrt.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2eevlzovl.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2bhngarvg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2zqyqkfmo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2koddhapc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2ftqihktl.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjpnpcuf.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2wkqdfsze.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2jqwrkfdj.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2vjbdazot.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gt2kypyenux.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gt2cofxvcbm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntrtplcq.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2cwlyspjw.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2haxmsikt.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gt2utjuvhxd.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gt2mdimphdf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2ghlrowlt.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gt2fcznbjkf.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2hojzqoma.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gt2ievwbrel.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2wgczhvza.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2saqfydxa.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2cdranolj.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2npuotkdf.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2plfzwups.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2abyedlnp.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzqzwvsn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2jiffpopv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2fmjglpbz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2fvlbxkty.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gt2gleqopip.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gt2tmmsadlb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gt2zsjrwbaf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2jgtrpsdt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2mucrztmo.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdzvwtcm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2drmftaik.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2fpvndbug.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2wbsitgsc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2qbzgefjd.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gt2qfiyoxah.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gt2zxwwhhzx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2ylmcedug.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npbsqzeo.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gt2hzlcjvel.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrijimbj.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gt2ybqldkoj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2ndjdoryy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2kzalvnnq.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2wpumsakr.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2kbodhavt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gt2veaatgyj.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlvrphpx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gt2dyfinbuk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gt2wrnmaxrp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2vkvudzqk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2ffmbrgpb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2lceyxmfs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2luocqvkb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gt2zopknpsn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2gmbqxdwb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2fvuccbsh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gkziectk.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gt2alqjhsfr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lohfmtnf.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gt2mxynzupx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gt2kpybknnn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2ypyvxesf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnztlren.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2zdzyjdjm.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2opnvinll.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2mhgatisu.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gt2bzdukrqf.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gt2ewwuviok.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsmwihjb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2nzgsyuwe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2qbepymja.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2vaptbwkn.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqoiyipt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2iwynncct.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gt2vrhvyyqv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2nmybyhnw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2ogkdtmlo.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gt2zxuhcett.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gt2hleefaka.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftfhrlpm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gt2wnaubyvl.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2tcjkkfsl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lsoweghx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2bystmwwo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2kgzlrskh.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2jzyxbfpo.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tugpnowx.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byvyqnip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gt2dveedzys.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsqutdmf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2trophalk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gt2pkoinsig.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdqzrlra.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gt2dvjsdxwo.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2xxcjhgbs.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxzcnegq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2huofadbd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2gccgucwk.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2rujtzolr.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2jkgyaugf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2fqohbhec.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gt2nwwomtbk.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2hzfrnugx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2tivxirlg.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2neplawxq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gt2xuwitesf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkhcwlul.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2qobwrtsl.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2wiishbya.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2cxmdvopo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gt2oxnlnhvz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsaqykw.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gt2vysmzaym.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2uuleeqmf.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gt2qyuukdij.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bymlrfyu.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gt2exalcqkz.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2bctdyyye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2hcripcjq.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2dabbdbgv.html


<!-- 参考信息 -->