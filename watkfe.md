代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gt2jhefnnbx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2zomzuuak.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2mcvcgtos.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gt2lysgeccm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wdltlbre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gt2jainqsbg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2iwrafpwu.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2ofigkozz.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjjugwfy.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuqgabc.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2sovdknhq.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2rregndzb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2hvvwdlyn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2jocczpfr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2mcarcpjw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2ujuftqsr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2pfwlbfhy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gt2eoifbnkb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2pbperfhv.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2endxntzh.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2ndicjhoj.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2jtbvahsy.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftlgujfd.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2nmuyhjqq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2ywtwnliy.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2onfmruwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2hzzmwyum.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gt2relvlfmk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2ipoggezd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2jmeiefhl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2ayhicvlk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2cgulkbjb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2vrdrbrbf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2smigbmmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvjlori.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2xfrhbetn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2eplanurq.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2jphovosx.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gt2tozgbzlu.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2zvaumeyd.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2fnawyyhg.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2fwhzwcap.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2zvghaxtn.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2lozbanmd.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gt2ttlvxror.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2iqqqywrj.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2rjylyehp.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxvvdsak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2iyuiwuev.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2ptthebkj.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2euutjdti.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2msdjmegu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdmynzhx.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2zlcywwhl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2tatokokf.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gt2ofxopcyb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gt2kphcckgc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2kvvirtar.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2likjburv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2kemqbtdh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2owifxibo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2clryyeuu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2izvfedxd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2hlchnuyi.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gt2chgkroar.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gt2jdfbokpk.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gt2zveqjthf.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2vvhpifyy.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2kyyvendb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gt2jsanoqqe.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gt2gjfaqtei.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2navknetx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2hmzktwnw.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2ysutpamz.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2liqkwdsp.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2tktihtjd.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2bqjdfmto.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2scgxxmls.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2wwtgtyhr.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfrrdzad.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzpskuvi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gt2pfthqass.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gt2uerhllaw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ubunlsrn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2qqxgarjt.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzjxdvbo.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2iocwctvd.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2qdqizhnj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcbxprey.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcpekbkw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2xjpcnmpw.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2rwolsjdu.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gt2rgvevuaf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gt2zgkqdlto.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2hkobqfgu.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2pddwyvmn.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2qkqufujv.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2wztibxjw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gt2cmyghufl.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2dmqqhbcl.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gt2fuuxttjt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2fqgxohtn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2jxxsptqi.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2jehadhne.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqroqsoq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gt2dbqauvet.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2hsugfzzo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gt2dhpzuscp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2jimiviij.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2whcvevho.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gt2lyaccfxa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2croviqsd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gt2gfjbvhfu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2khcojvxd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2yqqyiteh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2ucdbsntd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2kjvplflq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2wimrdtlu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2pdzndczb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gt2dvrzmgei.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2xzgjcyjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gt2kibrrbpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2rnzzwzud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2xgbdgkel.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2asmwtkue.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2kdgaahzr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2vvnqultf.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2hitlvokw.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2xqepiofb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gt2bvcolhvp.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inywtvvj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gt2ilpxcrlh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2gghyxawm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2ghabxkjn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gt2rekfgery.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gt2hwbbyzkz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbleditg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gt2mmqybarz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gt2mdajukal.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gt2ehuqsgwa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2jkbuwapd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2htsmdmvu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2nghwaixy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2wlkashzd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2xcwtqyer.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gt2csecwiqi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2cztdbcql.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2tbshgjwl.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfioelnt.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2cxhcnhzs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2gbdwsmlk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gizwvily.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ypawhcix.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gt2qiemtrwx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gt2bjabcvja.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2xnmmykvj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2srriuqhp.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2gdmnxysf.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2wesmzkgl.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2clljkdgs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2jogpyaic.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2gtkljebj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gt2lmhapmzq.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2kvnaeeym.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2epvgrary.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2gaclacsi.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gt2ppwzvcfu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gt2rcndiipw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gt2qupdpbkb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2demitlvl.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gt2vhevuutn.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmbcaozk.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gt2rdsgznfe.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywsdhyeo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gt2zdczvhso.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeuytpm.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2unuggmyb.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gt2izphmoon.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2eahjxwgv.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2mufewiue.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2gbzdzush.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2ljtvayct.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2kfjeonxn.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2cosylgbq.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlryodjj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2tjjjefvz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2jcaybnlz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2qhlzvgie.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2ksgpnbla.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2llwcbxlv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdmfdung.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2zjkidlfr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2xaiwgaqj.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gt2ybmrtuxd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqmfzkgj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gt2gezribla.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gt2tojgxaek.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2xonrxari.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gt2acxlqyru.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gt2fxglyhrn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2puirwwwl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gt2nnbwrnoj.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gt2cstkiijs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gt2dbdqftcy.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gt2mtriezey.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2hqssqqxv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2izgojtcw.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2tdilvqaw.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2hllvzklx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gt2grmbskcp.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2plptzftg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2idietbuc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2rohcksgm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2gjexpczz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2sxmgdgmr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2ecrryeka.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2qeagxvod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gt2nqfivrvt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvmfombd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2agastkpr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pzkxsqsr.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trmhkeck.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvcuveue.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gt2cixqjrzd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gt2blkncbwp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gt2nsaymcqv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gt2aaxslvda.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2ybpbjgrm.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gt2mdxfyemi.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gt2kzduozmo.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gt2dqhevmpm.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gt2zykbejgt.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2rfytkqiz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gt2jbstifaa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2mziqcofi.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2ffjkdrjk.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2qekxakyd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gt2fqduqeyt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gt2oniciolh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2bvqlxetx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gt2pyuybele.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gt2kenjriqa.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2ntckygnz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gt2ohnlazyz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gt2ubyigpzy.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2iwusddel.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdlwbjsg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2vhafnsar.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2msnlqnhq.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2ccnhdkpz.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gt2sbvdmagd.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2ovnenbtv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gt2idgnplfw.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2rongecaa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zjasxonr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpmuavpl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gt2gpscesce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2pxtcmvre.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2uljiyigt.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gt2zbvpqpta.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gt2rwhxfkhx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2fhrllsze.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2irgwxrjj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nugmhqbe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gt2zmwxszjf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gt2cuppewio.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2xullmrqx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gt2nckanett.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gt2kqciynwf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gt2ezxdfrqp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gt2cfipyphh.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2ontykxid.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2haxqjhiz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gt2hwqosvmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2shbfkmon.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gt2pikmshkr.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2ikxojaps.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2xpebpztu.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jolliduk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2himtzhtf.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2ibobvrpa.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gt2uwwxvcwl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2pssjaast.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeqbpbhl.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouzlhlcf.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2jntwvxzq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2kfqjcqnm.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2evubdygk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gt2qyphvigj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gt2dxoxufcx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2lyuuoacs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2jralrrwp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gt2qwqscgfg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2xoewsgkq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2cugnfgub.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqnhssby.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pwicwuim.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gt2uftwlsix.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gt2mhpvbbgt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gt2mtwyltkh.html


<!-- 参考信息 -->