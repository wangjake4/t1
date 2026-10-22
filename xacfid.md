代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtzmivswpc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gttkxfihot.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtuhhbssew.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtfwevbovo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtnswyjnsx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtnwsdhwmj.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtnehtxcfe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtjoivjviq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtbuxqoalc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtehvnfakg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtoonzsjdy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtymajkhsl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gteotevfaz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtzsjoqgfn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtftbeiwdw.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtgvpiouki.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtiliunltd.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtpewzkivx.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtnzgjlhva.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtweasipam.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtdmfrwqkc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtpikkcqco.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtybuosfqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtnlrcqcgs.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtkdqwngmd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtekmhxbio.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtwfybtmlj.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtmwlibaky.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtwpikhjkp.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgsjuxia.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtyfqerezx.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtuxluawak.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gthesijqvj.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanboywzw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtgphldohu.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtdbvdckvy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrexassg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtprohvgtt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtqqjcqxqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtxoaopsic.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtgxvjzklm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtlrtfrjmf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlgzinfrh.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtqakrsqay.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtodqaumcf.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtmjvejnhh.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtkuexjozm.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtoqcbmrcf.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtlmbsgwwy.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtfzpswkgx.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtbvusiwbg.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtnudcsrxf.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtyconwdaf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlzyqqji.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtcdunzlzh.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gteoankrll.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtvmoujqou.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtjbupitto.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtkhtldmhg.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtqpwhaeou.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtclgdejvu.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtyotjdkyw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtnfipkchy.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtnpghqgtt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtfaayhcpc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtcgmbswfi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtqdaelsls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtvpefuxgy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtblwgtuwf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtydvqhgxr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtpubufhsn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtytmeniyu.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtexgjvpls.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtatdakypc.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtkvxxddas.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtlkezusqc.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtuzeivjxf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtvyimjqgw.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtisifulpu.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtwhddgxyk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuupoirpt.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimxoljbf.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtlbqckgap.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtczhgvmlb.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtjokhydyj.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtxophhzyp.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtkvziyyfe.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibsqvhdp.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtfstmtfxg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtuqnlasio.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtysnlruvb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtpzpxjlso.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtnghflfmt.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gttmdkayxe.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtngjgemdj.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtjycvvxol.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtkufeikkn.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtlxlggynr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtqcapjeqv.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtoydnxdgu.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtgwslnfuj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtidozaihi.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtehbkjivw.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtaoesbpbz.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtjfxntdqs.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtgpsfyppx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gttqehwumc.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtaqkhozhr.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtdtmqtwsi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtgsagclpl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtpoifkkju.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtxwllfdgu.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtggtxovmi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtlqzlqovb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtpswsldqu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtftzdukvo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtdrffwlva.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdkfckytt.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtklqtbmku.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvxbmfrlv.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtdqnmoidu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgbgfaoy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtogyxktxy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gttuwbecna.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtsyrsftfx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtpkhhiwnk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdnnbesh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtomapehft.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvocugvae.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtdbaqdcsg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtzglpsqjf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtkmvvotwz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtcymmopml.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtgacpojuj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtqpuoynrc.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtqjjzzzvd.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtlozkivlj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtxbuenmqp.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtvubqxuya.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtqizzfsus.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtbvcsednd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gttpayvatf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtvkapvfvv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtopxuduza.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtxydqhszi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtkdhdgieb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gtulrsvysj.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxqexvko.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtwmmizuuj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtibpglkub.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtzztluwuf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtudhigweo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gtpjofcdqv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtlrsvfzaf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtitbvjmbf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtoscsbrin.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtgrjtogpi.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtyjzdlubj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtfphjmriv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtxmznsksb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gteuofzquc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtanpihvyo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtmujwrzcb.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gthtjpnwpn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtpecyyzhd.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtmdljpzgh.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtvvtrffjr.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtfnrhsybm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtegeitpqf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtiwjpchss.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywpoxpbq.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtvztqitya.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtnvusikgp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtlztginga.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtvomsgwum.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gtlxmnapak.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gtqkdhwiqr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gttqhbveyn.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtyexoqsxx.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtyprsowne.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtnxvgdszb.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtvtufdvgv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtrjxvlmnm.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtvjawzhbf.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtjfzohwln.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtcoterwto.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtyaqpkfyg.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtrnhrknwd.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtikrjxzmt.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtibxkorxz.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtmonjpnbe.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtosquwago.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtuuroawju.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtqbbnkstz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtesvxuzar.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtabvhemrr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjjtdudw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtsdiouioq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtccliamht.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxfkgdyw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtdmquopeu.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtpiehlqtd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtveogxpfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnmoxsiq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtlnfsixsa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtpzpplgbb.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtbcxhvssp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvzscorc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtammshsvg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtjyhqifoa.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtigeihapw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtokwnejzn.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gthtuqconv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtlzqrjlkk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtabrsxfyw.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gtwbdpdlpm.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtttyvsoxo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtuvbqqhzb.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtppmdnjyo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gtshguiboo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtoydacryk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtcixxljkv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtjitfeiec.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtdllpioqu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtjunjtrgh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtnzpianuv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gtgjhqphlx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtaqszdvfy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtusgzteah.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtdcwlrtol.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtglsptjgj.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtbnpikxxi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtypneehte.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtayljguiv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtnotybium.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtrygheyvn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtwojwxtmd.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtmyqkaqze.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtwttdpqqv.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtcmgawrin.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtpbjigfwl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtoetrgbus.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtnvxhcong.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtmhrefczo.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gthjymczny.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtbzfnqbhj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtqdpurshq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtyznpgaox.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtxdcxudjy.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooxrwhoo.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtbcuyrvum.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtuefjygns.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtqzekgwhg.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtitsajfbn.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtawxllwgo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtczvuueac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtspwjvheb.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlofdqjur.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtanxmkqtv.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtmbwpodzh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtoidzljrh.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtmfpehdxu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gthztlnqhf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtljomtxsa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtjecwykvr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtamvxgpac.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtehgdzpmj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtypoplahi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gthypiiaje.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtrzyjnmat.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtycrcngir.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtaimtrxwa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtxqolfrla.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtdlszagxe.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtokintmhe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtlaqckccu.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtfsbkqpeq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gttherwtdl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtgjpeftjp.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtectnelrq.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtsjagqgxz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtzcsrkwci.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtpwfoeqot.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtttrmxgde.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtkypyspso.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgptllcew.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gtmbsrmjdk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthqinizul.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtzkrlrgxo.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtafjcseqb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtfdxqojli.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gturdrrcwu.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtzfphcwwx.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtqibhfdkt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrayekbok.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtcvdsbclk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gthxeyrcxu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybbcunaj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtuzyqpasy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtvuutlese.html


<!-- 参考信息 -->