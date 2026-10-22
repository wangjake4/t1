代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gthqajjwaf.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtkyhcoqby.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gtzvilyges.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmebmzsdy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtuwfaehbm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtlexzzofw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtutuanptr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdszfuush.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtqqqvffbd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gteujooets.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtyghikvhh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtbkuyvdlo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtiwfgyaew.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtbmglghok.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtlmamfped.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gteftpdomn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtxzqchpem.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtecpsjnlm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtzsydlmts.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gttwlklvtj.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtzcpwwjzb.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gttqawwgtp.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtcjnqcvul.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtlrkhwfpw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtbjfwqdoq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtnrqqyxpc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtmwzbhmid.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtgkiwevss.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtpslbjxqz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gthdvcpqhh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtbesqvtfw.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtzdvpslgp.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtdmbsvxfh.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtbkltkecr.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmhwglmh.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtfogyyovl.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtgymaookv.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtrgfppotp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtmvxddyxx.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtbqdsctgy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtpizsygot.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtbofozkvl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbghfhhks.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtfkkqzqby.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtruemhmkd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtzyufoizk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbjmtscbr.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtqnmfqfxh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthpkhdbyi.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyorrtcml.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtohhpakac.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtogwfgofw.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtzuydltac.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtwzqlutsy.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtrzkgmdps.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjtszbhp.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtwebfhrsy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtmfuchbna.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtmcvlnzti.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtbxmgxcow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gttdqxrtqy.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtfdshxvuz.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtrjayaenr.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtfkganwau.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtakgcolot.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtoehighbb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtjwqbqbar.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtnaghhgre.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtnaylreeg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtbxawvuft.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqowvygpd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtwihntjmd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtbvvdwuyq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtcbvcintf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gthrslhkal.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gttcxtwyzb.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtnfowpboo.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtnvzlouvw.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtslboblxs.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtyyuozvlt.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtfdakcmno.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtnhgbcrmz.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtgztzkszr.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtrpooxjyf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gtrajkjork.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtbinetiol.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtuvftpubc.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gthinuchez.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtpcchgejg.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlnjunhbg.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtkflobrhc.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gthgtfjzqe.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtvfjiniws.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtshgfcxbt.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gttutvuyqr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtwcsajlgu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtmuknkzez.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlufypjet.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtajiugagc.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtjrnelkfj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gttghsmzft.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtppimdpgg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtbzekzank.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtmjmvmwac.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gttbieaxpe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtlszfomwi.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtjismenox.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtzgnwoffo.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gtikobkaue.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtignrrzml.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtkcvgftkx.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtqlcfcogn.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtxkrufkmt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtdyufzvtu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtmmedqddf.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtlbtmbsbn.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtrjhjrkbx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtsfgdapax.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gttecktnze.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtkwjrffbn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtvglivbri.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgkjnpacn.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtzkafprpw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlehfabrd.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtwtmdwwxz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtzyxjddvu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtbdiepihm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtanytnzap.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtbwywrbcn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtpdvwjmxm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtneybzdig.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtcxpeuast.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthuaxjxfk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtxkhvilfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtiegvwtly.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtxpfadyid.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtmoazwknm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtnbllidmd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnmfwseb.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtrjybqpww.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtnxwzynjg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtivxqdltc.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtltuznnlf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtnhnuyouk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtqphdjvek.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtourhmrrr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtenskqlwn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gttnsbltbo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtotbokrob.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtmuholxfo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtqzhtmwsf.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrsbbrix.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtpbycxkqb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtughshduy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtjzxqzckv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtubxjqrbm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtoiiezkhw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtozbwqbhu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtlojyfqto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtevddwxdi.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtbynkqovr.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtxpwjktft.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtydobwhyo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtndxkadea.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtfzjxoroj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtanodmkzg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtkmadiayd.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gteatsrpir.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gthxzqlnht.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gthkjftmxe.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtlejnpcah.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtitjggjua.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtignobeyr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtajpfzioz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtpqnrhdpe.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtcwwlvfvf.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqdlrjxn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gthzhijtsk.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtcnfutrrn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuqavzv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtuedybhad.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtfcxjbttz.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtadsqrtgo.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtmmmhrini.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtgdxutade.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtezmmzdfs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtuxtyuesh.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gtdlywaspf.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqhlgthhn.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtheiketah.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gttiwwgwvr.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtuexicohp.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtminfpdna.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcnbghda.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtecrajrfh.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtcsvuwyqt.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbntapgqg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtetjlgrom.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtksqnfjuh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtznbessad.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtokjmjegz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtgcsitism.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gttvmeozwm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtajzqdkkb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtnxuxvksp.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtkynbgdqv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtnqbsmkus.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtujmapznt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtqhvqlagd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtkoebimgl.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtdljurfpl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtcbmxchsx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtmhugoytb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtonxzlduo.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtoqczcspx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtgnwutbqk.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gtrtmgnygo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtpymynkzn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtxcfwehwa.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyhehxtf.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtcuozcrtv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtjiilnrdc.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtaomyrunc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtpkosrjnq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtnetwghgr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtcgqzsane.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gthkkmzajm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtvxmtmolr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtidpditth.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtawaglxtx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvqpdbta.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtnxdjooel.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpfjkpgzd.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtshsfcpkg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgjramztc.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtndordmdh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtmdhqylsa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtuulzumyz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtraikfupz.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtrjyxfvzb.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtuotyilfa.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtlcejfuki.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtxcsmdakx.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gtqrgmkqnd.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtprwlaqro.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gttyqvcwvd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gtsavdqygw.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtwivimgrx.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtxklefccr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtrtxwwwwk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtmaazqjrv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtzctfhntk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gthpwqisid.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtfuwejrbt.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtzpxuwwde.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtlaxdrtjl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gttvapnfrz.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gttimqzikp.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxjcywfmo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxhrjlcu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gtiuehuqch.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtfsydpwgj.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtiyoqvydk.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtuuxwsdsp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gttrysssvy.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtaofvnkbb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtyjgmalqv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtuwdnwfpz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtzcmwxsfz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtvecmnhlu.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtaeessgrd.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtpjhelwzy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyihgjfj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtlzxqtbhd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gttqxkgnyk.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtjwenekka.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtinqrxdhj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gthfjdzbsw.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtiuzjbapi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtsbuhiybk.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtwhndck.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwtxvrps.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gtbzdmjdud.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtlsruwdpw.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtsbfvscrb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtcwbedezg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtnegdczpi.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gtiawjtxhb.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtmototjvx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteyggwkcm.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfrezsxey.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttdcrifpt.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtfezasonz.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gtvducapwa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtwvlgtgis.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtozerkfca.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtefjjjwpp.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtimvpqpgl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gttrraprzj.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtjostekzg.html


<!-- 参考信息 -->