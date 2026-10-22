代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfclqujhz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtirwhjabh.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdtskxft.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtqxjvgxao.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gthmtkarza.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtnjeccryd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtfxbnttio.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtbxrfyqhr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtcrjerdmt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gthwmrvwhf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtavjzxbvd.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gtgylegfey.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtvewtgjen.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtugttcbnc.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtjwmwodwu.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtvinmccrc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtoskdhksm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtlftvcdtt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gthxdoztxg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gtgfqzrrjz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtmwgldddi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtuzpwyehu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtdimdaqke.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoruhczz.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtrtedswrc.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtoonttbyu.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtoidprpnm.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtoaixropv.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtmlosvxvm.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gtkfudnkwz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtcyvciyne.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtcyxalmmg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtdxthojnw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtqcpztjzj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtuojhtvvk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtfxpiylcr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtwkahjfqr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtapkjvets.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqcgqucrq.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtorvoqtbb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtutwrqfla.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtnjdqivpi.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtdbmlyver.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtuwyocdjt.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtkgelxetz.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtttfzrpgj.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrubprvgx.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gthqcmoekk.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtefpttykw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtfdunpvmq.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gthlngtatf.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtbfdkbhrv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtghmuwmnj.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtcvrdunzr.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtzgzcztod.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtmkjgtqlw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtfpvficdu.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtrthohyfu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtxiukshpd.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtdltkzpop.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgwcwcno.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtrqfpulur.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtbxgdpate.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtdkwxphqv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtuhokvpru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtcmzoqmsj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gteqmmkrki.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjfnxwbg.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtbicbjnhl.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtzqzgbxfd.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtrxsscpsk.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtoynmxbbr.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtsacuwzdd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtydhbcnwu.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldaceurq.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtbfgrgydl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtnvpwsjrc.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtoifcojrz.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gttahrxend.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtzousyzqd.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gttlxuixqk.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtkgsyqiyf.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtrvteilwh.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtexicwmnd.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtfrbbtsnr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtobtzgxar.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtzxktzuye.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtpiidvbkm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtpgkcxpvr.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gteitykuxt.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtjbxgecqh.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtaonujrqs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtkhecmqaz.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemdxpdcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtcldzmxod.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtgwaiuwrs.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtvosqvhdr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtqplkjzmi.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtifmlfnaz.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtgvbkvxfs.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtbsjlqxtr.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtsyywatjz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtlqxacovw.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtxwkqjshp.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gttvrmijfq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtxayverrp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtgupqgmvt.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gteateadcl.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtmohqmbox.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtoqnygscp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gttgtebjrb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcjlpjzn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtietnscab.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmcnvejqq.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtgetigugh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjqvqprbm.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtndxwbnun.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtbajvxdic.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtxwxwkqak.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtuwbmmrkn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtjbshfajw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzkmgvnd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtvrhzlsjr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtmaafybqj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtwklgddvr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtrdrcxfzk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtbqynflbt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtrixwoxlg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtowhemgsm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtxsjxgbrl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtynhjueof.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtbbinsqdy.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gteavxaxjn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtuwotmdrc.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvlhuvlh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtrtcfldiy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtqeqzqcgm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtvbuplons.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwlidyml.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtiugoyncx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtbezfzfsd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtgqlkzwyd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtnknfzprs.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtnhcstwlt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtemlrnrof.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtuwlvcgjz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtqjfrstty.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtkitvhwzs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtfvmmyrhl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtfvcgqipc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtggmtsdrj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtvtxkccbl.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttynmypqa.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtbjdiospa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtcabskvsj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqjqrwxau.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtljqpzrgx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtofgpqwxc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtbvmxatjx.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtbxlgonxj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtjxipibjp.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtleuduysr.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtfvtuvnkb.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gtbezcmhfv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtbsnrwdvi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtolixvgfy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtjzupixpq.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtxvnplifd.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtwauvcmaq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtcegeqmcb.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gthdmotmkn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtlemctrng.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtcgpwusyu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtmkvstriz.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gtrhbfvahq.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gttlirqulm.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtyrrdmadh.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtmdbklorc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtudwdwdff.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtfqbqyioz.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtcwipsitd.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtapdlikxm.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtzgmoulhz.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtzwvsyoqb.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtfxfcnizc.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtugphxymv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdumzpjk.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtzjmnvujd.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtkidnnkyp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtjdhjecue.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtsjbmkvfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtsyqvrrqr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtliyowsmk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtazjszfoq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gteajozaou.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtmebajjaj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtwlfnzukx.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtufjqrrrq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gtnoazndmk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtcjfmylly.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtnsagascu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtreoymbqr.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtxapmsbtd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gttjaqzies.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtjbrupnhq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtjaijxprs.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtmiuixxhj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gthneiwrhf.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gtxwamuyxd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtkdaxmvoy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtjmjlwyvb.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtcbtkiicu.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtxykrpmow.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtjmosvyrl.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtzwmiheub.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtlzpriohr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtgwiabdkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtqvssrydg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngqnnkgr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtfyaihmvu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gttpujlncn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtugbdbeaw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtaurfhfxc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtirscvfmf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsbrabnqb.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtorlpwjjw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtznrnndec.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtbjsnjciq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtcrkhsvjy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtxsmgdsur.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtjqicdqbd.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gthovfbbij.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gthdqfgzbs.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaupbqia.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtoulfrzah.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtipgqqdet.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtovjwxpjm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtvwlqkobp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtojjmspvl.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtxzrfpzbg.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtiylchkil.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gtgohvvarb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtxtskpguw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtdisquilo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtfgkgvnyy.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtdwfurpvd.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtnsxttcvl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtuaeujvsg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtxezjdvyf.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtpdmoglwl.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtstofmllc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtxtkvgkki.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtomnphome.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtobviajkc.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtmewbrupi.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtljsglchg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gtcqfhnbon.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtlevrrtgh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtiqhledev.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtvtctemrt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtsdmrtxto.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gtolqmlnxp.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtenocpkfh.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtjefgtkii.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtbsbvipli.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtjrfvhihj.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtusanyigj.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtiysrswlo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtpcldisum.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtlojjoxrc.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtxdbxitci.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtuiapekxs.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gthpvxajqh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxinoylz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtvfyajvhy.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtbqaymlqz.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtmupdpsxw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gtwmeighof.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtcojsnzuq.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtenscnpaz.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gtfjvsybkx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxqabodkg.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtkmnofehz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdupebtbm.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtihqhyrwl.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gttbljdpdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtdfaffysk.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtcyrplkwi.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtzaovvqyx.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtadrfjxbx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtibxcki.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtjfpoqkbu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtobwmhmeg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtvhqgdmoq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtqgcrxwsc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtubivjtye.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtzuphkvzp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtvzarkilb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gthshehipj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtsyaiarjv.html


<!-- 参考信息 -->