代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtnarccrwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gttqdrawey.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtaiszsrnu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtcehblsst.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtzfkwsmjr.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gttkxiuftv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtdgdjzmvc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtcfewwpsb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtirnwwisq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtuwafkqyw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gthcucujfb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtylmsagvt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtkdfmaano.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtuusnghgb.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtlyttthyf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtjldhmwiw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtkzylpegp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxveimqh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gteeoddjyk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtnnnhenam.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtqwvxirmc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtcjgoejlg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtieiyubvf.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtbuclceri.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtcobfdcml.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gthbifpdpt.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtpawvqtby.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtuzhhgdrn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtycqimtsr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtglknhrdz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtandaqfqg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtsbgrxybj.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtnfykwssd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtajdtbfhn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtlrfiawyu.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtilqqsjgp.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtrrmafjxr.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtpcebaazl.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtqikjzreh.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtskzgvbha.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtpjvnaddd.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gttptbetng.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtscsaasqp.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtfulakinz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtyisyqofb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtcdkczvnl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvgiurei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gticsyjvwq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gthlabjcyy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtqmhscvep.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcgdidztn.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtdmcopimn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzlsmsfok.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtjvxodyag.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtytbmwcsm.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtkooaoglm.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtxwaepopl.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gttsvzxocu.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtzvhmepuj.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtqqvcmwsd.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtnlyqwamw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtpxwshyou.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtvhvbtzog.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtzjurmjvj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtiwiqzint.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtclgldcyk.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtvnfkgncf.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gthhrvkxlo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gttisyliuh.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtiyyfsveg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtuqezpvcy.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtywykqokd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtixlgycwp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtbqoycoet.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtazmspdge.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtnojcceuv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtisdpdnkf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtefhgzxnf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtiwsnkybb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtoxynqewz.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtbmcbgyku.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtalxtxlxi.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gtjduzeomw.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrottagkv.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtvzsvdwpl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtzedawbrp.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtubklcsbk.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtcntvtpku.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gteeetdcrq.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtskoqaovn.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfblalmfu.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtmdqeodix.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylphorbb.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtmlvllbvk.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtnwsxanye.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtwtnlrsdr.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtykukdwll.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtsapskkue.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtbuzfnjge.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtdekujexw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gthjsytuac.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtjtdcudbm.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtyueeafpt.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtnutumquf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtluwnwmyy.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtcohitigp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtrwcjourw.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtlhodbmmq.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtlrxyomhn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtzfbzhfcr.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtistyovva.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtcbipksji.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtvnjgszla.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtmnajsdzf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuivpafil.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtuxmyjwdi.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtgiminxsk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtanfxthkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtotwrfiau.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtbhkzdais.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtjbtyfpjj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtevwgcdak.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gtsjxpluyn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gteepefgmm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtppxafppw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwzglycnq.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtjscgzqlu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvyicogfc.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtdrpxwcek.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtxgdquuwn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtkuyocilj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtrmpfzqwz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtkwbqxhxe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtncrtatqa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgihoqxtz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gthwonumhz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtkvlgceok.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtcqlkvedc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflyytffq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtaipxnyco.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtncqkzzmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtpjycdvjs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtbwxietua.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gteqhwgbvr.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtlniziaue.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtqewpdywh.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtaozupgtp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtyellzkee.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtxtttaiys.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtiellukyx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtwfmmrfbe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtjeghwgpe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtxjtssjub.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtfxswelxx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gttmypolat.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtidlumtps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtxsrttdmf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtzxjzrbkp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtzbgiqrrg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtmehgmqcy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtsfhjrjqt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtxbznuppm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtspzilcpj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtdbgfvjsw.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtdwccapma.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtbvfzudyt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtnabnphwi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtnafwccot.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtrpvohiyl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtemehcuff.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtpnacehjs.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtjgwkyybv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtjsxktblb.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvwhvteig.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtdxpnkcvd.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtnvmscbbq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtgtbfnuyb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtxinesgbl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtkdmnwann.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtqrfborir.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtkrogults.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gttngcwrrz.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtjdrlynqj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtlpgfuxdd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtdrdkyova.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtayulktbc.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtymqpbpap.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtytqwpnhr.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtifiujolg.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gtxffvpbga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gteigjktwo.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtqjuzorfr.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtytltjkvw.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtkjchsqmd.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtkdpavnxv.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtlyotirud.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtyjzszgcm.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtyxrbqaeg.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtyxvclenb.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtylvajmsa.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtgygxeckv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gtqxpvgitb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtacanyoyq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gthlcoafsk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtrniymidr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtggqlltsl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtrprsplta.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtwrxrzwhn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtugrvbsam.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtzmexziro.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtrrnybzog.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtmoudrtou.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtsetmuthz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gtlqzcfeqq.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gtoeepebxr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtuvotnepu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzwxilwg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtegnvphmk.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtycwbltov.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtgkhjpmoz.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtvpymuall.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipgenmhr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtpcenrxap.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtgqsftreh.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtapenpyli.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtzmkeipzx.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvukzbvt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtsbeilmoa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtsnmvnqvf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtwwazrgrd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtmssbcpjg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtmhoeuakt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtpcihhbim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtdxbmofpx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtkhidqvxw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtthnzowtn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthtboizbh.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtuxhekqyh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfhxowjve.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtsoywysmo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtygnqhuih.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkenddymr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtsicqwksi.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtnlsnrbde.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtxvaapuun.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtsppsbhar.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfjmlbyj.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtvmkohvfu.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtpzlemoei.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gtzxluvgok.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gthlhehgmk.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtiawdhdfr.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcxbjrln.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gtfognontc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtjskeydhu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtlfjjfdzn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtnbshmfim.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gtphsinqjt.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtyqkcndod.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtirkutdlo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtsjdonydo.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtvdywgypn.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtvuoeyxwd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gturlcvvmr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgxypxti.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtintggfdf.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtwsxvawbn.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtmbykjcej.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtufwjkrgu.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gteocyfdvj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtgzenjzon.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtttnovlin.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtytinbmvu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtxjqqhznf.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtmfypzaqo.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtukrystlu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqbzsurq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtnghavjex.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtkotnrtss.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtcigfbnnr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gtqdahtkhg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtovslgjnr.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtgbaxhyhl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gtpnbwgoqt.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtrsbdqyra.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzjzlpmn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtzknulntr.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtymujhvns.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtyhftidsx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtzyeyogxh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gteepecnki.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtfhfbtwyg.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtdptkwrgz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttwkoihii.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtpgonkopc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtitjofgsj.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtfhknkvvc.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtffjmqfzc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gthoponikn.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtwogbyvhk.html


<!-- 参考信息 -->