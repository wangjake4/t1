代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtqmlpmrlu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtwdgimzdb.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtafnjgoho.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gttrlmqtzg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gteeporbjd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gthygddvwr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gttnbrujnj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtjdbsemtx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtypfujodg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtxnkvbbwn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtaeptiiss.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtrleucwyv.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtcenmgswe.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtbnobnnla.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtxzqguxwv.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtvhmoufas.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtlaupygtv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtpnwmxgqq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtbajtjaye.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjbsphwl.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtjkbpnqlq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtgsjristr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtxtxvgimi.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtmywswhou.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtzyvrhpkh.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtcsnrwmps.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtojazaozh.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtqaewzeaj.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtvfdvuooa.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtuhewqiiv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtaknrdpnk.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtvfqfrgrc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtzweyorrj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtzdhleeur.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtgfiduisx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlseflux.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtbecwfpec.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtmtamfvkm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqbuyiujk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtnldmjmkj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiyktplo.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtcpuqbtpa.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtkulkohwz.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtzvvpjjbn.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtfzsrbvel.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtlfpsthyl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtvkxrafaq.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtcfurdjzl.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtihzsgtjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtoawtqako.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtqidmxsrt.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtqbbitjkj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtxfdddmev.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwylpnci.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtysdgokms.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtiknblbmr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtdwkijxrt.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gttvkfwsmi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtqrefmbcm.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtmzrydkbq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtlkvbzees.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtjszerzcm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtohcnzdml.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqgzwxpda.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtqxygmura.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtghdseoxn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtgaojguig.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtjaolgent.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtnkocauol.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtiuvglmcl.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtrlwobzwe.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtoarytseh.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtsuuhoeqo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtxvfkazmm.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gtdobrwtgw.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtbnmpvgzl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtrhxikebs.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtpjlineln.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtwdvskldd.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtsrihilzz.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtlxrlicgs.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfjmixae.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtfuqhvtxw.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtizepbxfm.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtyhlnoeto.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtacqhhrxq.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgznsckg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtbluvvabo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtnjnurkka.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtpiwhskie.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtyjzqtlgf.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtfnoaygfk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtqxszqdph.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtdxvtpqfa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtnnegekbp.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtzozmpvts.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtqdgtqwtw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtezdaxygp.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtrwuiygbf.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtjfcugmqy.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gthsjgzavh.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtqgexivtw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtkaenxcfu.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gtwshilsjj.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtoiqapiyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtmmhagjqi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtttuwhvmd.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtywbckcsq.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtgjcwzzdd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtyfbbihzy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtxossfuju.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtpxhsbgpd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gtsoecnzce.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtotxdrfpo.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gttmuxoswi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtflezxorl.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtbcwhsuio.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtmpvgxtop.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gtjbxytzgf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtfxvqmcys.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gteixfwpui.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtauohwvrs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtgkjwsgoc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtbzlurnhi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtgopqxxeo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gteyixqqup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtlwphfsdi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtevojjveh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtflwybfcc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gthlvjktny.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtbtklaigr.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtvduomymy.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtcoxfwshg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gttmxkztxm.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtyazcempm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gthvdkdzvb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtnaeenaft.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtjgxqwepf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtcplgswxt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtzdqejnqr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtwdkwhtlz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtsqsrmsuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtmkeotwzw.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtdupvhnmy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwnkpwye.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gthozcoray.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtefqbrl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtfreglbdz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtljfwlazz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtsulwyaep.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtcqmgievn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtgvcsqocc.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtknfxkwau.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtaxfnpncy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gteuletvqz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtmckbyppm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtzppikghd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtndpmeipb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtxygdmyxp.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxpbashim.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtrnlrjahu.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtjtezcvyh.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljajpozj.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtaeummuvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtjoleymrd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiswhwslf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtxqtvxkty.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtnexhasav.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtxonupraw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtjrfzamvp.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtfodakkzb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtbmhypncm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtqgppjocd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtdcabqjqk.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtcujohqfp.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gthdjlfdsh.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtfmlhpbuq.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtfogrngmv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtiowcnxpr.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtccqjsfyu.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdijvqqek.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedvneumj.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtwtsqoqyu.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtjssvujke.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtxeklxiuc.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gthwufvkco.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtzkbdsptn.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnwioalgr.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gtuwgbumwi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtsgdwoawq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtjewubqax.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtadevrtfs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtaqpkuwwn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtoshkhbyg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtbfnvsirq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gttqtzwuoy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriunzscc.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtbuqmforn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtbjretlbl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtkzcfzejb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtqagorujj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gtefptburt.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtyhyhknfr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtbmfjdfxu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtxldncfxe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtytbjanym.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtuwkqukwp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtgxumwcre.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtnvizcsbc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtsufcqhgq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtokekkwap.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtdbtvtcuq.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtmulclmgt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtixfhoqeu.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtqcofmdzq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gtumzmwqfx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtgpbugkad.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtzfggphxd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtbixxdmkr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gthhhaxapq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtsprlpmlg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtknzsvqrw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtklvupcdg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtifbjfpah.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyespezkq.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtrqvlzipd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtczestpta.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtrqgcgobf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gtbwswszsq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gtokxegdkl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gtrcyrpdrm.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtwmntgpsy.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtavxszpug.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtdlickkfy.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gtxoyeplff.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtlugaaxqh.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtlddujtpg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gtgvescskd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gtbhfttfcg.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtetujrhzi.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtlekatmnf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtqbjfavka.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtkqrtvhot.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtnahxqjqo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtumrfkabz.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtleafhzfl.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrvbdplu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtsnbsveqa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtivlxvjnu.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtuoxmcvwn.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtvtxysonc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtqzikzpgy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gttfwpxgyk.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtwzgxmeav.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gtqcqgllrm.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtrdftcnnp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtumxqfhja.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtelklastz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtdoltouxj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gtasglrllg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtylmyhfim.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gtsltdnykj.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtrpnxxkqq.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtpczokiwa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtayzmvqmd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtwdnwdzsu.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtgmenwysq.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtvigfcmfv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtmjcrgfhk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtwvaeicfg.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtpyhribqx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswybkmtg.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtpangrfpo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtqdapesxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtyeziuete.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtlutiialf.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtffpuxcui.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfytzbhmx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtmszyxxzx.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtgvqyctxi.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtvfaijcwt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtowxoioee.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtaeizgusa.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuwlhxunk.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gttiwcvcmb.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlynrprf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtbrmlzmog.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtdahixlzr.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtotwyuuhw.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtfizhbxsf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gttrprmkks.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtmtfisjwt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslxurpau.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtnkowgkho.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtzmjjwtfv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcyfeett.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtmybybkoi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtolfybypz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtfjhcomry.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtqnikkfqs.html


<!-- 参考信息 -->