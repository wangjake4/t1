代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtztcswocu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtyccjmpnz.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtmxiogvqz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtopbjnggu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtrfxmdstj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtefustcgz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtjbizpjsc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtkvlxoblv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtpadjivxg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtzkpeqnuv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtyolcymmd.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gtiedoizph.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtlyonxasd.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtgeclfujg.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtetzssymm.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtgmopxbae.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtrwqgshhj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtncubmyti.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtdoqrbhag.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtcikexxgw.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtftyfbufz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gthiopshms.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtgughtgdj.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtodmpzqio.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtxneqpeoj.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtoyhiswyw.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtdwrsjxtg.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclnrdjvf.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtshqvenxf.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtdklgvwil.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtqgxislqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtvrhcghqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtsqtlhxzi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtpilgrvop.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtidwbktei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtprvjhvrx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gthecydkkx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnefeboh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlhnzwgcz.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtlgtjcywl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgralfyjj.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gteblstojd.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtovxeykeo.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtzuvdfbwd.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtasuotffe.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtodmydade.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtbeywnckp.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtzcmqucob.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtqmseealf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtzfwopaio.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtksfvxbfz.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gteluoqpda.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtmrwwmnse.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtakbcnntq.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtwxfojrhz.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtegwciuko.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtrdurqpbr.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtcrqexkxg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtxmplmozu.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtmqtfczvk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtodqiqgve.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtzmingcvb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtbdxfuhrw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtmltudbto.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtjbpfujis.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtumfddcrq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtdhruwmhl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtkbrtnpoz.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtkpouyzjt.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtfrbgrxss.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtiuhhmdbe.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtbkcgdmvy.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gthnlqadkh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtdjatrmeo.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtuxvbsafg.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtzijjkxav.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gttjgdzden.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtvylkpnrh.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkiwoqllz.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtmbbuumdp.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtplumwgex.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtwcozaxdk.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpmpjiyj.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtdffellku.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtklrirkpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtlacsewli.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtxxqgtsyc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtfnorkedz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtgxmjnilr.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtfbilqsuw.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtarvuxscz.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtntkieabf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtlzxlygpx.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtafjhdudl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtubxtkbbc.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtwenbvsqz.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtcrsoxslj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtcsakkqyb.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtqiyerymd.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtinonvaup.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtsyzymsrf.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtjdkfeisu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gthttbqqwg.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufmemjqh.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtiwzwdjcj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtmjjalvhp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtrgevgutg.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtgetluvhw.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gthpkuynnx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtrjdslcyw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtdppwikns.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtbemipduj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtgseisfrd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryjqtrtc.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtszdqlsrn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdrumrirk.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtntnjxzox.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtzxzvrtcm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtvnevslls.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gteygljabd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtneiuglsc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gthxplxvka.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtmobvptqy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtqgouufur.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtypmkpniw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtalvjhjjm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gteipeypma.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtecalwiqv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtbhxuigqo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtcxyiskdy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtzlrwstlq.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtrqneiylu.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfbxbxvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtiunlkszs.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtovjhytal.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtrmlrpzyq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtrxezuqbe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtzqkspkfm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxyuashu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtphcvfdmn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtxbdnyoum.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtqknyytgx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtuyqsnhra.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtjujvvniu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gttrrphbrr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtepaqsify.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtvrekyanx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtqphifxnw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtrxezhbrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtflywvbuz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtgupveumg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtlfzhipgs.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtpvnzrlwe.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtfrdnadjs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gterdrszoz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gttefqoixm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtbcvbmuka.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtxnxyvwkh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtablrkdvp.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtfelvrcqj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtgwuwrvfh.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtzylcejaa.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtigegmerv.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtipsnobzt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtojexupta.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtrikmgikf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtvnwulbfn.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtysohwpgl.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtuvzojcny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtugsdnlbq.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtvynayoxs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtjvitavqf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtkowcfxbp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtonkjrbvp.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtuxqzobck.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtntoloiku.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtlywoilvc.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtltzemyiw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlxwgbfk.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtidvzifzo.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtbqbvfmzv.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gttigxpcss.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtqzutgaas.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtoxhnocjy.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtnpnxlaqq.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtqujuvger.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxigrqrj.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtqaelxqqo.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtrpvqzmxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtfocpsojf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtqlktmxpn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtfcdnhohb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtemiazbrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtdznpxchz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtbgycqexh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtnbetflgi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtxdhugcee.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtncsbfczq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtbwseefyx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtzaewanur.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtwnnvqdof.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtvhguikby.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtkowwldnd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtljxrycvz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gthdfujlbn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtjmmcdazp.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtwpyotufn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gttlmslkkw.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtqgbfzjwv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtpgnezlfd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdymdkxh.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtidplgirr.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtjmhfmoad.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtrfrxxxkj.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gthnmdlmbl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtbajwvahl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtodpievqu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtaeufuart.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtlcnbzskq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtrqarofqb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtuvpmcxsb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtomdesika.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtrmfdvxad.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtdwhekewu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtaptvwpag.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtaztrupvp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpsoicmiv.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtsvzxmmkq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrqajmhn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gttowtzzos.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtnyukrhsc.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtxvpnwtoy.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtnuvcsooh.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtmvwdinbo.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtbqxsrwpb.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtquvunsuv.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtwjpxezzz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtijbekwwx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gtqdajonur.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtljkessyb.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtwoucfurd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtctolekko.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gtbuemihlr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtjmlqbtzq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gttcjqdrhf.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtbjgnmjgk.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtalgnnynv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtibdjvjdn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtohyksnco.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtbrrtyako.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtsrmwhumq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gthjjrwzhm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtkwpwlsss.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtvvvurjlj.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtcudghzcn.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gthjsdczbd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtznfvcwye.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpkkptxxw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtzxdnbztz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtrbbixstv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtfjumirtd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gteeadfpvr.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gthjztxkdt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtydqtkxbu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gthfjsrcnk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtronamkgw.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtqamiuhyu.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrimeteju.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gteecafjsk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gtuyzzphbt.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtrbimzgka.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtfdcughcz.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtdbelrkuz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtjmxnbgxk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtfmwyvkxk.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtauyamsyr.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtqrmarsqv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlesoykx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gtubvgqrcb.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtqsctujma.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtxorgquyf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtokpchkjo.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtyxyztsza.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsanaemfv.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtfhekhktf.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtlcamuxie.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtafhlywkd.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gteuqcdjju.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtdnixhtsw.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtqvxzgzyq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtcuwfjgvd.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gthkgyobtj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtaonzclge.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtcpoqkoze.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtcwlszslq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtmwazzdzq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtbdnehlmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtscjibsqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomdsfmqn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtwcrlwqcq.html


<!-- 参考信息 -->