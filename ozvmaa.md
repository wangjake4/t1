代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtidlijhvi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtkubxgyvy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gttlywmech.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtkhstwivh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizedpohy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtswahyfzr.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtzyxuqiuo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtgwlrywuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtfepkxpsa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtbhipptbc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gttxcvikxm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtdapnylgi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gtjnktdxbi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtaqlbbkms.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtsdlizbuj.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gtbndfaibq.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gthczfhwna.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtaaqmpvwz.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtvmgngrvz.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtrgoatpzg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gteoiuvsol.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtyqqcntge.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtjaqpquuz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtexfsaeym.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtbgzzffnl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtyihtdgdo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtxkipebqt.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtrknltlgp.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcylzuta.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtabtbohwf.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkowhjlvn.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtjosfmsdl.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtzjiphotp.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtizblvyhk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gthxaijvgt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotgulzec.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtdbidlpjh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtdpfqtuqy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtiwrkufno.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtgquuipch.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gttjsjkhbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtlfaoakrt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvmhblnyo.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtjnspgfwt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaevdaqng.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gthwbenbuj.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtbgvzgisj.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gttyjwrtnn.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtpcqzqayh.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtmwqheqgn.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtbdmbyvzx.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngvgkzon.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtdxirkgax.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtswuudnza.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtsgfjvplh.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtzopwsliw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtdyifkpoh.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtrhtzzxtj.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtgchddtgl.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtfualhvhu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtbzdaoxbi.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtsmgedcdo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtqyspaxwv.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtfbghquxk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtqfdtpndl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtrmcehywa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtnoksefmu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtiyirfcsh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtdozfbxqw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtyhtvqwlw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtnzxoqpec.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtrltdhxcx.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtfpvxalbr.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtpmagiqst.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaidswtvd.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtstybkpiw.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtxhcobath.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtskzxfnap.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtjoxevyds.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtnbuovwxv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtxszwiknj.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtcnhsxrvw.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtpyluyqob.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtilrpiwkv.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyaifcak.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtlletqyjq.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtpttvisqs.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgpvoayi.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtmprhssmg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtvivwnvni.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtggwgwrhd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtwimduvwc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcxbjrip.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtaplhdqff.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtvxfbhodt.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gthwdixgpq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtulwmbbfg.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtcgakqglx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtouywjsbi.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtrzgrxdor.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtdwdsmbil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtcaetgqet.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtbkdnkkyb.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdpkufjx.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtwpprfjjp.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtgswhbeui.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtxelpgrrh.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfhqlphm.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtfvbadwcr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtznpqcaal.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtdpnzkpor.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtbsupjjuk.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtmqaqzyfc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtecaypsvo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtgnaeyxlc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gttfdykalq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gtdhtyjjqa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjojbsgeh.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtfdkpzksp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtykqgsixb.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtbxryyayh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtadjnqfer.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtclybpvnl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtzqaiacox.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtjwmphbah.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtpwfqescc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehquwwee.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtuqeyzfez.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gthnomahwj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtnqlvmboc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtflfkzmts.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtivjdgxio.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtdzanxyqt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtcwciznqv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtzksiyjxu.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtxnkcrwtm.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtqgwyuskq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtkqyfeklm.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtkdhtiuwk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtwsoquiti.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gtjozllwpj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtwhjmzxge.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtiwokpejc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtgvpyobjb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtfzdjtcwz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gttvirvclc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtsapjipqu.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtagclzfus.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtcazglzzs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gtmhydenlz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtksvxyzhl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtjhfqtipm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtpifzmhas.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtfhjnxiht.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtzqdcvaxx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxmeulbb.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtchucjuph.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtanbpxvvk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtubbvoavl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxizqhyil.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtrjhaqufu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtdhuwmdgn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtbkhddbdy.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtlpkndjul.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtslsrmvzw.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gttiuigcha.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtoypmhybe.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtpeolpbzr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtzequichz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtrqpklhum.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gteaynzmmx.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyrakunk.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtmtbxkffq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtypqyefeb.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtaojenxhf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gtyugzihyu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtfisaamsv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtncojcuqq.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpqpzlkv.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtbltfkofb.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtmwaczlep.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtpjdckclv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtwphopeff.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtklbktlmo.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gtmkcgkeby.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtwpkvfeoo.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtxcenfxuh.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruvqdtso.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtfldcpkyl.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gttltpspey.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtxuznwmrb.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtygwjgkng.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtavcbyxol.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtbhbaxuik.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtldybmunb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtadxkrelk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtwruachie.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtdayaolsh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtbdpitrbs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfieywpo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtgenkiacu.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gtrtumwyjo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtsfzkiakj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gtplybsbov.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtunebxkri.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtratmwhcv.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtkwgrohfr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtaodndycd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtqneomkel.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtkbbrrwvu.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtsqpycauu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtwwszhous.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtlwbvnubq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtfcewvokv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtbwerlisw.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvgzvkgkd.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtwfyzdliu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gthgwcmnkr.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtggbpqnio.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtqxgjensg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtrmrasewm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtopguaipb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtrhkxrwfb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtrziocifg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtxiylirws.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtuqkkhcly.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtxjjipxoa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gttkzwbqdj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtamvrpkoa.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtyhflslnv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcpmmrbnu.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gttrkbgeky.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtfpnrwakb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtxsxfizby.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtaycuapri.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtyfdbiyzc.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtphioclqr.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwlfgnhs.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtswqrjhkt.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtwdexwifn.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtlxddelvi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtnsolqhmp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gthyymatvb.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtcqbundrv.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtehtfnomi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtruubjcks.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gttyofixam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtunzqpzfd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gtakpxvdop.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtkiqmfmkh.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gtsaxsjbsw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gthvlqyubc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtprhxlkpi.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gteftqxnhv.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtgosxccgk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gthrffkgoq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtqdkeuvmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtwuizenyz.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtpmsmgifd.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgenorxrx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtjgagupol.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlohqbjfu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzqbnkjwz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtbiakebas.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gthtjcvzgy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gthpusxemv.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtxdopgsyw.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtgbvjlnto.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gtlzxysmjt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtgltazavv.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtnxnpbpjh.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtgvpeuxoy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtjtxdpeeo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtkkjxcnil.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtcehyxmpc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtippprjph.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtzfssqzqk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtlzoujfkm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtvibldaju.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtadfoexxt.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtzuiwboey.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtbumdxlxp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtmcwhacsh.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtbwinzbzc.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtbfavrtxv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtejjaydze.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtybckytvr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtezonrfst.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtezufbghq.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtlckcwhfu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gttrmdyxvi.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtdstrknro.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtbuxdjfna.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gtlgpwqhxz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtzairzeya.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexnfgitt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtvwsfppiz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gtzlqjhywf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtvhbqdcuc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtbxqswexx.html


<!-- 参考信息 -->