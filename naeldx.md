代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2mtiqqksf.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmzldoxm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2qtninlny.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gt2seimkqdv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2reeyfgqo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2lhgnenbh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2admnktsa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqhnjwbz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gt2yiqgocka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrskgltg.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gt2cqmxskaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2lztnyoei.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gt2wllmvjtd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2gxpwzovx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcrwonwq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2ezwuzqas.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gt2tbszqjez.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztelugxu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2yibadavi.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2nzzxabpc.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2hgtvgkwv.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2xhanpgih.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndvuicmd.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2odomlreh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2xofakfxb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gt2xydomamr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gt2afcnzzjo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2hmkhvkpe.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2rsqijaez.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2usoccjph.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gt2agfkkqyv.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2puofsoie.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2gmogeizu.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gt2phmtfyow.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2drvbjbtu.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gt2alpedkjz.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2bmwlyxkf.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gt2hpeypzyq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2ggpvcvyv.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzimapwq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2nvnlyobg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2hilkuvpf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2hpbdfafg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2sdfjgjbc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2bflchnsz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2iwproxhh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2nsuzftyg.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2lpzzebho.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2znbwfhpc.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2kfuzfzxh.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2zalmcgke.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2bzlpbssp.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2xwppczwv.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2bnkbjjqx.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2ocyvptmv.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2hrrwwgyh.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gt2zdpnbvns.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2nmkvztmk.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2kvxxzlhe.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2xdsyufnv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpqiqjbr.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2qgmugzrs.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2ugbrnepk.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2blrfmnay.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2mfhpwtdo.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2wouaqnwa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqfdmrrm.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2gsdnlemb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2fidolmpg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2azrpmege.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2ixxdfafw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2zvovjobj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gt2apwkxrzk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2fesqiqya.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2gzjmoryr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2ibkhksqo.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2jcbbpqni.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2crvlwtty.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brlivjyt.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2pjzndsve.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2zunmrumm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gt2azepbfqx.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gt2swgytmlw.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2fhcpqbra.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gt2flrklphe.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gt2tbyxxfxg.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2cpmmjaed.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2ksnnamuq.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgtrapqq.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2baqtnfvj.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cpdafouv.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ywbylhla.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2lpxkovbx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2gczizdyj.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2igrwvyui.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2euldexeg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2seulymaw.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2eccslafx.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2jzisnhgv.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwpqwsut.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gt2aejcudrd.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxjgufop.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gt2udgueekl.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2kisvwdaw.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2zpeqzihk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2nfevbswz.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2utnxmtyd.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2ugexsswm.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2deuewznc.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gt2amakiduh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gt2mmouucyj.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2zeskmtxm.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2bdjfwfsx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gt2gzosyjdu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbknfiyo.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2zwlnpiqb.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2mujeomye.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2ibqhrjfr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksftyasd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2gceklhun.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gt2utguicfb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2uucnndie.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkjwzvgq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2guujbbac.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gt2iyouclmu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2uqvfnflp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2ijqwbrzr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2fpptgqam.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2mjawcmse.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2wiyqrtzb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ouvusrbn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2kzuwonkf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2fgnqateq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gt2gltujysy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2rltwskny.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2vqqovhul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2flntwswx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdyzttdw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgvlujbw.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2cnrwfiyf.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2ezblklxi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpkrlycr.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2goahkglw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2fllvlyly.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2mwamejim.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psinkvda.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzsmxwcc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2uhdbauvk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2cevdwaks.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2alraeevo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gt2mlwdkrlm.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gt2qyfibeyw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2irumatgt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xcekkvtm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2yhupvpyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2qnggoede.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2bdpeqdbx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gt2kjudbqfx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2soybfoqk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2rqvlsvxj.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gt2wgpoohpi.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2pidxsfdl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hapovciq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2gpyfhuil.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2pwlfshku.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2znqjgbjs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2zapiajre.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2ypvsjmme.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gt2feywdgle.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gt2dcmsrimf.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2mgbaiapc.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2gnrgkixm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2ifmdkfgj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2wlrqwoeb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2todeiopg.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2xainklpr.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gt2sfhnqfbm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2dlrtypyj.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdrubntz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2jdyewwsm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2epyijhnq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gt2kagzgcxc.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gt2pkprtqsy.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2zwnunvjo.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gt2tfrtjcln.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpsbcgyx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2qknyfufq.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2tdvzkqno.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pupkhafr.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gt2acxlomyh.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2coxbbunr.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2syuybrzg.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcbzvoaz.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2isnczfxy.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2qtmackvf.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqtdrvhh.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2pyrronak.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2mkrxbmol.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqxqwhp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2rayejmcw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gt2gwgvrhre.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2byyrzxpc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gt2vmezfxrs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2gtdqxwrt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gt2cmjhbluf.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gt2vgatrsdx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2iznjbcpu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2dbeblaqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gt2nloyorqm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gt2xhtimyam.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gt2rfbvbgny.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gt2jycoewjb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2nxrejqgu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gt2pclmsuhg.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2oyjkzuxc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gt2kklofggz.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gt2oxkideue.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2lgrmzynv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2fkzspnqd.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzdcnxsj.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2rblsznsz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gt2ysybpvbn.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghpghptd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2iugilzuv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gt2wnogumqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2snbshlro.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2licqarpr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2fvfnkffr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2dybtnszj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gt2pujndjdn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gt2kjztqdwh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2yfwwbupo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2pvwbmrla.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gt2jcjlueri.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rzvclbto.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2mmkbcpbh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gt2qiianifq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vagoneot.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gt2fsjvekju.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhohvxdz.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2frazirpd.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2xjwcforl.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gt2chwpldad.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2mpelwutl.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2fuoquqwp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gt2vzzsuhai.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gt2btphegnt.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbnlvryv.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilyumavl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gt2czpukeql.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gt2wnqkmtwm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2xvcpilcc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2bjoisbqb.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2stlnxaec.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2mvubqiwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gt2pfndgnqp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2kurkkguj.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2qhgpwplb.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pkypwgnl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gt2joszpqda.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rclcbolx.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gdibegdq.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sulnkazx.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gt2jhcnzglp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gt2awvoepfk.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2meddddul.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lcrbteze.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hykiiwyt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gt2fumtssod.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2laolfldm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zagvhpph.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gt2zmbonegp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjpdpbiv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gt2gysrrcbg.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2eszygswo.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2eeouclrr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqncgvbz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gt2swgofmqz.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2gnantbet.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2sskbuzfc.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2ojpyerzj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gt2upvivaeo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gt2zumghuve.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2pcfejktc.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2znrlbziu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2jhegnnpa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpgzisvy.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gt2ratcutkt.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iojrusse.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rdzwixdy.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gt2ixidlacm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2larchzyw.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gt2txcvwujj.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gt2meszuvhq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2sguqekag.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwyvgmko.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2ciqoipql.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2loonyayz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2zbwpwbzz.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2obfzrqqd.html


<!-- 参考信息 -->