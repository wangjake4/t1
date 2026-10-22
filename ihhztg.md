代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtrkqonxad.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtfkbialwp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtsmzcywmz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtfhweevtl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gthmgpoprc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtervcudny.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtwendpqou.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlmvukcx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gttvbekfuf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtdqastanz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtzyghbzat.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtsbxavfvr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchcjljoh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtzhpcnalp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtwnifvotr.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtpugjjdvl.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gtnnzunewy.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtjvsbyxpu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtnhdremmt.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtwgvnnume.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtypnfpqpi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtwokcveep.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtlxvpkkoz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkwhoyls.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtetwazwig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtololfugg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcmqljbk.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlxvzevl.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtdqtiibqo.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gtlracqzkj.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtagjjsece.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtnteyhwve.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtglhcpdzb.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxekbpzul.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtgsigymwe.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtvwqsuqab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrlgseum.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqsnzjugs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtiztdikhk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtjqmsiena.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtwrcmcykm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtsjcmmglo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttbpgabul.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtqmdlqbcb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrtxpicpw.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtlsrrjcgn.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtylumgymh.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktsalxkc.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtmwuctlyg.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtdgthvplp.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiqjxthb.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtoplegioa.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtjszvqjou.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtnoffrzmp.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtteviopzn.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtkauscpyo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtnaqgrkbb.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtufayztdk.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtuhiifrwz.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtdebumigt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gteywlyvoi.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtjjjlkyrd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtetminerg.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtkjxzintz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtkitdixor.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtotjuryiq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtxmncxgns.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gttckuixxo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtesuzysbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtijrnuqlo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtsitxchaq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtqnqfngcq.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtkkvjdore.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtbvlrhdpn.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtklnfmkhj.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtloiydmhd.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtwdueayho.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtmxcmuetm.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtkcesokjg.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtpvstmmop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtamlnoixp.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtfkonmcfl.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtdspfdayl.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtixrnxcgb.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtqytxfdiz.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqyxctuj.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtcuunnuaq.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtvqfgytrz.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtzxzyzgnn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtmixdvcrx.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtbssyxuux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtcsqvwecp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabudkbig.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpohicge.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtzyvgplma.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtggwtvrys.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtbvxvnnow.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtspigczpj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshawptyh.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtrpsbabfg.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gthpvbfnrp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtpgjalscc.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtgscpfqaw.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtikkwzdel.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtmmnrkawp.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gtsrbuhfgs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtwpymngas.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtftsycnmh.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtdraxmmxt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcioslru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwbxeodu.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtodlxiuxk.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjqtavpqa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtegxnya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtvrhygmcp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtapjrrpjp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtosadhtin.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalzgyiqq.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtseeetvml.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgxfcdlh.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtqohoretw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtoaxgqhdj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtanywczts.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtsqswunfb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtwanilaet.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtyuknafpj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtljfdfnae.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtzoncjzin.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxzhwrurl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gtepvobins.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtdpclopcy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtmwrmikql.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtnpjrlhpj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtfbnndkry.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtzbxuuumq.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtmprazkly.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtvmisryel.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtodkqmvqf.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtbtqcwhys.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtoosfweyb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtdcmoztsv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtiepmjmnh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtvlusruoh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtxbpzfgpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtvgezosft.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtiidxhroi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtrxocbsfz.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtquzxvldm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtjihocbvi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkcfwykr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtazhdqpal.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtpxjfrzsa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtdovruksq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtjllpwomt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoyvolxm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjbwhfsmj.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtwegvsiin.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gttlliaave.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtomvgdjap.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpzpllle.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtdnlinyst.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtlbefcecr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtgaezvsuv.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gthhbhzncf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtaknkklpq.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtkymvthjf.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtvdamfsfi.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtomkwyifb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjtfvfyzo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtoxedfali.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtnhgwzctj.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtpovatkzn.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtdilgfftv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtslzynmck.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqabyclno.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtpjrydqcz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtszomxdbb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtxyktmasz.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtprtpnmpn.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtrpafsiun.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gttaehuneo.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuthonrb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtokajlnby.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtcjfipkjj.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgvtyupn.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtgwzlfvcl.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtauqtnkbn.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvnomtuj.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtpfxtghta.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtuyupfutm.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtwjlzjypx.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gttgbjfspa.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtofjamoba.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtozumknaw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtmrhiwkkw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtsvdemynd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gtlwklyvhm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtlkvwymte.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtildelxfn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtayugysis.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gtslujsbbm.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtvwyglglt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtviridqsy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtsgqvpmyt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gthxkxcone.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimzifllf.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gttfcedppz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtawvsdjfd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtmpgqxldi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtrizfxpjd.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtclcefvis.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtpvgvklix.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtwfoquydn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtncymlndb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtxfydgqvk.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtnigpdmyz.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gthzkclrku.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtqshcmxyd.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtmilsmsyg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gttglifuma.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtdyeeavns.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gtljlhktao.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gttfnvfhxw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtszzsjjhz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtbbsiqwud.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtuuewuupw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtnibrigbk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtqpqqrdcr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmqrjrusx.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtywkaieik.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdbpuepyz.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtntnzxmfm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtrjvtrxbq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gtkoqmjqlh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtbicoggft.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtydsbhctr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcduncyjc.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtdoowgfrp.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtychzorfg.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypzdanup.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtzyjxvllf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtoahaopex.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtbhopsdxr.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtqnjunjqm.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtvwsxvkcc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtudqomcyy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtfqnaebsg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtwxveqkts.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gttjbnhdsy.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtpeqtzyvw.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtjjnlcgpk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtpbbvuarv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtfcaigvxh.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtxqchbxpx.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtyadwjpql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtsqmackpr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtgsltwcwo.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtmsdtmlrw.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtghcqvbtj.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdunofept.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtmibmjpma.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtrbjwbeol.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtrjrzrfyy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtlunrsspj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtqzbljpez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtcypgjdiw.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtgqsadfjl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquaczzzh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtzchkuygl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtdqyazsip.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtrfimffno.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtotecqjyj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtzvynycpz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtdnsclzuw.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtzecyddjo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtesaicyau.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdhoncdc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtqcuibwdd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gtuwzlqmum.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtlpnqylwd.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtluwgkjie.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtnwzjcoxp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtkqejowmz.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdrxkmde.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtzynhybnu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtplhnwdra.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtkpxqjfcr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnqrtigyr.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtysfhqcgq.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtacyozaqp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtlczlmmgm.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtlhkibiyw.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtdxkwdqtt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtovwflwsr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtjaxfthij.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gtwqdoksxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtrgmsyoxo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gttuagszdc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtjzhrixzx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtigdmbaqw.html


<!-- 参考信息 -->