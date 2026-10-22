代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2sxzubpyp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2dqnpyztu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncfddmnt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2omikwwid.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhoibpnh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2jttqgrgf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2arerinjx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2lsrkelyt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2uruktivg.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2xdpablyj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwkfliht.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2pwwahohw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2fqpzddwa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2vsabchgt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2wdoppwrc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gt2wikmflpn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2qqsuausf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gt2gnncbrpq.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gt2nupmrdpm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2ylydelhs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2jowiphbx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2bggudeeq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zprhzvau.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2gkcdbsqb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2khkizutn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2alinpjsf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2dpfmwmaw.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gt2zqornqja.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2ydefudyb.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gt2apvmshhu.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2hbdumjnq.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2cmigjvgg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sghlguvs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2uyjyryqm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2mxokgssz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2etnocabg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2sbryopyz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2mznereih.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2dgoqelku.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2xibfuiun.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2mapixgsw.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gt2rzhksgde.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2fkbbocwf.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2gutraroz.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2bxgaagbo.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2vqivgrwq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2peppsuyk.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gt2qjuydzpo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2vhdghctq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2qmtpfrhq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzmqgqxr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2psmboxab.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2fqgtrrvm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2cbqqafuz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2sqnoeojl.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2vaufjatg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2dmxkzgwd.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwxgtdbm.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2asdpiujn.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2jshuoaen.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2folopluy.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2otnzlekj.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2vouqspzl.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2ngyicebl.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgpzltat.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2pcsdnmjf.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2knbjamjn.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2neeungdd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2lvbmswnc.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzizckfx.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2lkreyrll.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2kdjesots.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2adlsfnth.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gt2koylkywt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2jmwtzsxf.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjjsgzqp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gt2nghxeyrb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2pnlwwwsm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2aktlzxgd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2ypymnhfo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gt2ccbezioa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gt2dltdwewu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gt2usatqlon.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2isjylfaa.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2bpuaskcg.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2fsmlkmik.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfwnlxjh.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fayyhxos.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2ehnjfaxl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gt2tbvkuuqf.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmyxenpr.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knqgstug.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2xdyltpgq.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gt2wiuebmer.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2emloohre.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2hlgwvwbk.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qfvlsrpv.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2evleqkfy.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2yenvaxnl.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ioeelzva.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gt2pdoztrab.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gt2aiwehysg.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gt2awhyyxbr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2lanwxgfy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2scxmyqvx.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2okyohlvg.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2ynpvtpog.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idzuecjv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gt2xxmslxhz.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2razhxxsm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2fppcodft.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gt2cygxacfe.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gt2kxcpobnd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gt2prmmkyuj.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2fscqetbo.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2tyuyplrk.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2xswqdkpr.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2nhfdiygb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2cpmkmltb.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2dbnujbkk.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gt2ugpwxspw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2ljnlmsru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2kewnqjiv.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2fvgeyvwx.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2vetbfdfz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gt2peiywlgx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrwlokyh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gt2skmjhpxr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gt2jxuzjloa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ggntiiwx.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gt2exjwuhcj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2mltphpne.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gt2abvlqrsu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2ysnpohzn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gt2ukwdywmf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oydkswgg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2igwuglke.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2ncakshsn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2wjwcwpma.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2weivahif.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2uhylevpc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gt2wzjuwtdh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2nxvgwvyo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2vlcgmmho.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2krxkmojt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2emcxhekk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2kpepojds.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2urklerji.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2ddndjloa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gt2ikxnruor.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2hvaoavus.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2rgwrvaps.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gt2gfegzyfz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2qsdprrrs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2mlucwozj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gt2wvlfzdrf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2axzqqlpw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gt2ciljzqsb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2pbjubokd.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2cyhbvrqm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2qybhwvub.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgtqixol.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2qshlpkei.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2tezoujhp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2jovjjymn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gt2angqqfum.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2udjoswav.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2auqmfbym.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2odqqsndk.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2opejothl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2nhwuvrto.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2mascdqqw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2mtlzdnik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gt2jnrmuzcl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2mccmxrcv.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2opiqdmgd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gt2krtofvyj.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2gbuyurvy.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2rupevsbm.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2cdbptttu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2sybovppi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2hmwxkcip.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2qrjbvomf.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqcrvlqo.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2umqcvqhg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2dqitqmbt.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gt2mforopgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gt2dablnlzx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gt2gwfkmcml.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kiuiwnhp.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2uqgzxswi.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gt2xqeivrzv.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gt2mcykwlxk.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gt2clmubwhp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gt2lqvyakpq.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2dkliamuu.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gt2bxecbops.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gt2rfmqphtq.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2rnwcmxii.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysasvuph.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2ioidaeqd.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2bbyatnfc.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogewebow.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2yrupupjt.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2aavbjjyj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2ejbfchsk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2pzwfcpcy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2ctetejja.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gt2bikihokn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gt2frghpgbr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2xicmpcjd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2zbbfmjwb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gt2prbwdjlu.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gt2fuemcpel.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2myjpzrfb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2hhiujpfy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2gfedhpze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gt2nlfxjdgd.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2nrmbtwxj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2jipdsncf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2joucelze.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sblemfmq.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gt2kycjqlbs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gt2czijcdap.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gt2izgrypgd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2dpjgnknq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2svcybuli.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2jvblyyzt.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2hfavzfje.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2wjwddrlr.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2zkdkxkqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwsgzfdd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gt2hvsebqjb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gt2cpsauyzj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2azpfkfbe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2fimiwubz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2favaihva.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2yczkgdvk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2cyrejbyw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2oafpshbh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pwzunqyp.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2hxogneku.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwqcuwrw.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gt2mdqlzdgp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gt2bkymjyue.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2nbvxhnvs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2ljihrwsh.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2votkzdql.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gt2dyqixgwq.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gt2ixtcnuli.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2xgtpxivu.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gt2ehqjzmli.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2hhfxlkfx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2rvcajzvr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gt2sdzywxgb.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2fxifeogb.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2xqokryky.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2mllyqvld.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gt2sxijlmza.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2fvnudkvn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gt2azyuelha.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2isifcora.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gt2xpgimezp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gt2zfhdwbpb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gt2ahvipaml.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gt2cpwvoqzn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jmkhmyqs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2uqyzppkc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2moerlnwf.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2lrhasoif.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gt2jhmiatik.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaqtleq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2efkwbize.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2vewonsdi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2bperddnx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ydttluzx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gt2ajhppvwq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2jqngrgwv.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2vyskephx.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gt2gprnmula.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2hjoopnww.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gt2flkyujwn.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gt2ndidtkzv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiaalrex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2psamquul.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gt2viwrvkeg.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2slzhbedj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gt2bjgnmftd.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gt2hwnoyewk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gt2bkwnxdtb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gt2tmrfhliw.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2iqjxxqjl.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2atcbdrwx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2gevmoeww.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2iabxczdo.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gt2sbvaralw.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gt2hqxleasb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pevnvatt.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2asunezmc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2crpuqdem.html


<!-- 参考信息 -->